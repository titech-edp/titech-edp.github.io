---
layout: page
title: 2017年度「エンジニアリングデザインプロジェクトA」
tags: [lecture]
---

# Syllabus

[Engineering Design Project A B - TOKYO TECH OCW](http://www.ocw.titech.ac.jp/index.php?module=General&action=T0300&GakubuCD=2&GakkaCD=321502&KeiCD=15&course=2&KamokuCD=321502&KougiCD=201703604&Nendo=2017&vid=03&lang=EN)

# Staff

## Instructors

Saito, Sakamoto, Kado, Kurabayashi, Yagisawa, Terui, Mougenot, Park, Inaba

## Teaching Assistants (TAs):

Okude, Mizuno, Leandro

## Lecturers for Special Topics

Taoka, Niikura

# Objective

- EDP-BCの準備
- DTFで触れなかったことをやっておく
  - 観察中心のユーザーリサーチ
  - Mid-Fiプロトタイピング
  - 物品発注処理

# Design Prompt

“Design an innovative [kitchen/entrance/washroom(lavatory)]-related experience”

# Teams

{% for t in site.data["2017-edp-a-teams"] %}
<h2>{{ t.name }}</h2>
<blockquote>Theme: {{ t.theme }}</blockquote>
<div class="btn-group" role="group">
  {% for d in t.data %}
    <a href="{{ d[1] }}" role="button" class="btn"><i class="fas fa-arrow-circle-right"></i>{{ d[0] }}</a>
  {% endfor %}
</div>
{% endfor %}


# Schedule

## [EDP-A-1] 6/24（Sat）10:00-15:50

- 10:00-10:20 ガイダンス（EDP全体の概要とEDP-Aの概要）、教員の紹介 by 齊藤
- 10:20-10:40 チーム発表、席の移動 by 坂本
- 10:40-11:40 チームビルディング by 角
<a href="https://www.slideshare.net/kdmsnr/2017-edpa-team-building/" role="button" class="btn"><i class="fas fa-arrow-circle-right"></i>スライド</a>
- 11:40-12:15 講義（オブザベーション）by 齊藤（以降ファシリテーション担当）
- 12:15-14:15 ランチ with オブザベーションワーク
- 14:15-15:00 オブザベーションのまとめ
- 15:00-15:20 発表（数チーム）
- 15:20-15:50 テーマ発表 + 宿題についての話し合い

```
- 10:00-10:20 Guidance, Introduction of instructors
- 10:20-10:40 Notification of team members, Team first meeting
- 10:40-11:40 Team building activites
- 11:40-12:15 Lecture "Observation"
- 12:15-14:15 Lunch and "Observation"
- 14:15-15:00 Wrap-up of "Observation"
- 15:00-15:20 Presentation by a few good teams and feedback
- 15:20-15:50 Announcement of design prompts + Discussion for assignment
```

<iframe src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2Ftitech.cbec%2Fposts%2F620922071450010&width=500" width="500" height="847" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true"></iframe>

### Assigment

1. Observation w/lots of photos
2. 7 sheets of A4-sized field notes (per person) :
   1. Impressive photo that trigger your **IWAKAN** <br />
   ※**IWAKAN**: Feeling w/”why?”, “what?”, “something wrong!”, “something strange!” and others
   2. **AEIOU Comments** (long) and **TSUKKOMI** <br />
   ※**TSUKKOMI**: Critical comments to invoke insights

Please save the data as an individual PDF file, showing your nameclearly in the file. Please make a team folder in Google drive or whatever, and post its LINK to slack `#homework-20170624`. (Due: July 7 23:59)

In the next class, please bring your fully charged PCs with the Arduino IDE.

## [EDP-A-2] 7/08（Sat）10:00-15:50

- 10:00-10:05 ガイダンス、アイスブレイク（坂本）
- 10:10-10:30 デザイン思考プロセスの紹介（坂本）
- 10:30-12:15 Ideate & Prototype講義 I（角） <a href="https://www.slideshare.net/kdmsnr/2017-edpa-prototyping" role="button" class="btn"><i class="fas fa-arrow-circle-right"></i>スライド</a>
  - インスピレーションウォール作成 [15分]
  - 宿題データの共有 [20分]
  - Ideate & Prototype #1
    1. クレイジーエイト [16分]
    2. アイデアの分類 [10分]
    3. デザイン品質の発見 [10分]
  - Ideate & Prototype #2
    1. Disruptive Ideation [20分]
    2. ダークホースプロトタイピング [15分]
- 12:15-13:20 ランチ
- 13:20-14:00 Ideate & Prototype講義 II（角）
  - Ideate & Prototype #3
    1. SIPOCモデル [15分]
    2. Low-Fiプロトタイプ [15分]
    3. Product Sheet [10分]
- 14:00-14:15 発表（2チームくらい）
- 14:15-14:30 休憩
- 14:30-15:30 Arduinoミニ講義（田岡）
- 15:30-15:40 物品購入ガイダンス、最終成果物の指定（坂本）
- 15:40-15:50 ふりかえり（角）

```
- 10:00-10:05 Guidance, Icebreak
- 10:10-10:30 Quick Review on Design Thinking Process
- 10:30-12:15 Lecture of "Ideate & Prototype I"
- 12:15-13:20 Lunch
- 13:20-14:00 Lecture of "Ideate & Prototype II"
- 14:00-14:15 Show & Tell (2 or 3 teams)
- 14:15-14:30 Break
- 15:30-15:40 Lecture of Arduino
- 15:30-15:40 Guidance of Purchace and Final Presentation
- 15:40-15:50 Reflection
```

<iframe src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2Ftitech.cbec%2Fposts%2F620924061449811&width=500" width="500" height="847" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true"></iframe>

### Assigment

- bring your 2-3 ideas, each idea should have:
  - SIPOC model
  - Product Sheet (product name, value proposition, user test plan)
  - Low-Fi Prototype

## [EDP-A-a] 7/12（Wed）18:30-20:00

- 18:30-18:40 今日の活動説明 Explanation of today's activity (Sakamoto)
- 18:40-19:50 Activities
  - 講師が各チームを回り、アイデアについてフィードバックを返す Instructors talk to each team to give feedback. Please explain your 2-3 ideas.
  - 各チームは2-3のプロトタイプを設計・製作開始 Start making 2-3 prototypes
  - TAと相談して必要物品を発注 Consult TAs to order things needed
- 19:50-20:00 片付け、今後の予定確認 Cleaning and Future schedule

### Evaluation Criteria

1. Does it use Micro-Controller? （マイコン使ってる？）
2. Is the value proposition clear? （VPは明確？）
3. By the final presentation, can you make the core feature?（最終発表までにコア機能を実装できる？）
4. By the final presentation, can you validate some user experiences? （最終発表までにユーザー体験の一部を検証できる？）

<iframe src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2Ftitech.cbec%2Fposts%2F620925288116355&width=500" width="500" height="790" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true"></iframe>

### Assigment

- Finish purchasing the materials for your prototype(s)
  - Please make purchase orders so that the purchased items will be delivered before July 22.
- Start constructing the prototype(s)
  - You will be asked to carry out User Test by the final presentation.

## [EDP-A-3] 7/22（Sat）10:00-15:50

- 10:00-10:15 ガイダンス、アイスブレイク、注意事項（素材の著作権など）（坂本） / Guidance, Icebreak, Warning of copyright violations by Sakamoto
- 10:15-10:40 プロトタイプとユーザーテストの講義（角） / Lecture of Prototype & Test by Kado <a href="https://www.slideshare.net/kdmsnr/tokyotech-2017-edpa-3-prototype-and-test" role="button" class="btn"><i class="fas fa-arrow-circle-right"></i>スライド</a>
- 10:40-12:15 プロトタイプ制作 / Prototyping
- 12:15-13:20 ランチ / Lunch
- 13:20-14:50 動画制作講座 by 新倉 + 奥出 / Movie Shooting Lecture by Niikura + Okude
- 14:50-15:30 プロトタイプ制作と動画制作 / Prototyping + Movie Shooting
- 15:30-15:40 宿題と最終発表の案内（坂本） / Assignment and Guidance of Final Presentation by Sakamoto
- 15:40-15:50 ふりかえり / Reflection

<iframe src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2Ftitech.cbec%2Fposts%2F620930894782461&width=500" width="500" height="771" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true"></iframe>

### Assigment

- ユーザーテスト
- 発表に必要なもの全部（プロトタイプ + ビデオ + プレゼン）
- 最終レポート

## [EDP-A-b] 7/26（Wed）18:30-20:00

- プロトタイプ制作、ビデオ制作、プレゼン準備、レポート

## [EDP-A-4] 8/05（Sat）10:00-17:35

- AM：発表準備（Preparation）
- PM：発表会（Final Presentation）各チーム10分（10 min for each team.）
  1. プロモーションビデオの上映
  Movie that vividly shows the user experience of your final solution.
  2. ソリューションの説明
  Detailed explanation of your the final solution.
  3. デザインプロセスの説明
  Description of the design process. Please tell it as a story.


## 単位履修者向けレポート課題


### 【最終ソリューションとプロトタイプについて About final solutions and prototypes】

- 1) あなたが「満足している点」とその理由を記述してください。
Please describe what led to your "satisfaction" and the reason.
- 2) あなたが「満足していない点」とその理由を記述してください。
Please describe what led to your "dissatisfaction" and the reason.

### 【デザインプロセス（観察、プロトタイプ、ユーザーテスト）について About the design process (observation/prototype/user test)】

- 1) 上記の「満足している点」につながったデザインプロセスはどのようなものでしたか。具体的なエピソードを記述してください。
What was the design process led to your "satisfaction" above? Please describe it with concrete episodes.
- 2) 上記の「満足していない点」につながったデザインプロセスはどのようなものでしたか。十分に理解/実践できなかったことも含め、具体的なエピソードを記述してください。
What was the design process led to your "dissatisfaction" above? Please describe it with concrete episodes, including what you could NOT understand and/or practice adequately.

### 【チーム活動について About team activities】

- 1) 上記の「満足している点」につながったチーム活動はどのようなものでしたか。あなたの貢献がわかるように、具体的なエピソードを記述してください。
What kind of team activities led to your "satisfaction" above? Please describe it with concrete episodes so that we can see your contribution.
- 2) 上記の「満足していない点」につながったチーム活動はどのようなものでしたか。具体的なエピソードと今後の改善点を述してください。
What kind of team activities led to your "dissatisfaction" above? Please describe it with concrete episodes and future improvement points.


## [EDP-A-EXTRA]

- 未来洞察
  - 8月前半に2日間のワークショップを開催予定（参加は任意）

# その他の情報源

- Slack: [https://cbec-edp-a-2017.slack.com](https://cbec-edp-a-2017.slack.com)
