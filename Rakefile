require "rubygems"
require 'rake'
require 'yaml'
require 'time'

SOURCE = "."
CONFIG = {
  'themes' => File.join(SOURCE, "_includes", "themes"),
  'layouts' => File.join(SOURCE, "_layouts"),
  'posts' => File.join(SOURCE, "_posts"),
  'post_ext' => "md"
}

# Usage: rake post title="A Title" [date="2012-02-09"]
desc "Begin a new post in #{CONFIG['posts']}"
task :post do
  abort("rake aborted: '#{CONFIG['posts']}' directory not found.") unless FileTest.directory?(CONFIG['posts'])
  title = ENV["title"] || "new-post"
  slug = title.downcase.strip.gsub(' ', '-').gsub(/[^\w-]/, '')
  begin
    date = (ENV['date'] ? Time.parse(ENV['date']) : Time.now).strftime('%Y-%m-%d')
  rescue Exception => e
    puts "Error - date format must be YYYY-MM-DD, please check you typed it correctly!"
    exit -1
  end
  filename = File.join(CONFIG['posts'], "#{date}-#{slug}.#{CONFIG['post_ext']}")
  if File.exist?(filename)
    abort("rake aborted!") if ask("#{filename} already exists. Do you want to overwrite?", ['y', 'n']) == 'n'
  end

  puts "Creating new post: #{filename}"
  open(filename, 'w') do |post|
    post.puts "---"
    post.puts "layout: post"
    post.puts "title: \"#{title.gsub(/-/,' ')}\""
    post.puts 'description: ""'
    post.puts "category: "
    post.puts "tags: []"
    post.puts "---"
  end
end # task :post

desc "jekyll server"
task :s do
  sh "bundle exec jekyll s"
end

desc "Get medium's json"
task :medium_json do
  sh 'wget "https://medium.com/titech-eng-and-design/?format=json" -O _data/medium.json'
  json = File.open("_data/medium.json") {|f|
    f.read.gsub("])}while(1);</x>", "")
  }
  File.open("_data/medium.json", "w") do |f|
    f.write json
  end
end

require 'html-proofer'
task :proof do
  sh "bundle exec jekyll build"
  options = { 
    :assume_extension => true ,
    :empty_alt_ignore => true ,
    :allow_hash_href => true
  }
  HTMLProofer.check_directory("./_site", options).run
end
