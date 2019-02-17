---
layout: page
title: 2018年度「エンジニアリングデザインプロジェクトB/C」
---

# 最終成果物

{% for t in site.data["2018-edp-bc-teams"] %}
<h2>{{ t.team }}（パートナー企業：{{ t.company }}）</h2>
<blockquote>テーマ：{{ t.theme }}</blockquote>
{{ t.slide }}
<div class="btn-group" role="group">
  {% for d in t.data %}
    <a href="{{ d[1] }}" role="button" class="btn"><span class="glyphicon glyphicon-circle-arrow-down" aria-hidden="true" />{{ d[0] }}</a>
  {% endfor %}
</div>
{% endfor %}

# 来年度のEDP受講生へのアドバイス

自分で動いて，学び取ろうと思わなければとても辛い講義です．また，100%納得できるソリューションやプロダクトはできないのではないかと思いますが，この講義に時間と労力をかければ，それを高めることは可能だと思います．その代わり，研究をする時間がとても大幅に削られます．ただ，その分，EDP以外の講義や研究活動では，決して学べないことが学べる唯一無二の環境です．自分の能力とEDPに対するモチベーション，研究に対するモチベーション，バランスの良い点を見つけられるように，頑張ってください．

期待は裏切られるものです．期限を守るといった当たり前なことが上手くなされず，各々危機感をもってからやっと動く，そんなことがよく生じるようです．主な原因の一つはおそらく「モチベの高いタイミング」です．各々誰かしらに不満を持つのは，自分がやる気のある時に限って相手の反応がなかったりするから．僕はDTFではチームに恵まれたため，そのことに気づくのはEDP-Aでしたが，おかげでBCではチームビルディングという謎なゴタゴタを防ぐことができ，時間の無い修士2年の自分でも，基本木曜昼休みの集まりのみで活動を進められました．

デザイン思考の学びも大事ですが、チーム活動をするという観点からチームメンバーとは一刻も早く言いたいことを言い合いつつ、互いに信頼できる関係性を築き上げてください。

テーマの選択時にメンバーの構成を考えるべきであると思う。これだけいろんなことを学んでいる学生・社会人がいるにもかかわらず、バランスよく班分けできないのはあまり意味がないと思う。私の班は機械系が少なくてものづくりで苦労したが、機械系ばかりでも面白いアイデアが出なかったりすると思うので、程よいバランスが大事であると思う。

チームを作ったら，どこかでそれぞれが今の自分が出来ること（チームへの貢献方法）と学びたいこと，やりたいこと（興味があること）を明示化して共有して下さい．このとき，ポートフォリオのような実際に作ったことがあるものを見せられるとやりやすいと思います．その後は，それをチーム外にも共有すればより面白いことになるでしょう．これをやれば，チーム内での互いに尊敬しあえるようになると思います．これを思った理由は，この活動を通してチームメンバーがやりたがることが違うことが多くあり，やりたがらないことを振っても最終的にチームとして良い方向に行かなかったと思っているからです．

チームにやる気のない人がいて、宿題をやってこなかったり、授業中やグループワーク中に寝てて、腹を立てるというのは精神的にも時間的にも無駄なことであると気づいた。そんなことに時間を割くくらいならやる気のある尊敬できる人だけで全部やれば、たしかに作業量は多くなるけど、団結できて効率も上がり、最終的に良いプロダクトが生まれるし、自分の成長にもつながると感じた。

来年の授業性にむけたアドバイスとしては，どこかで妥協することは大切であるということだと思います．ほかの班では個人個人がこれがやりたいこれはやりたくないという意見が強くずっとアイデアを絞るところで足踏みをしている班が多いように感じました．お互いが意見をぶつけてアイデアを深化させていくことは重要であると思いますが，他人の主張を否定して自分のやりたいことを突き通そうとするのは間違っていると思いました．どこかで少しは妥協してまずはものを作ってみてその使い心地を試してみるということが重要であるとこの講義で感じました．

とりあえず考えたものを早く見せること。班の中でもモノについてイマイチ納得がいってなかったり、対象ユーザーや抱えている問題の明確化など理屈の部分が追い付いてなかったりすることはよくあると思うけど、見せてみた反応から話が進むこともあるからある程度まとまったらとりあえず見せてみるべきだと思います。外部の人にインタビューやテストをする上であんまりショボいもの見せたらそれ以降協力してくれなくなるかな…という心配をしたことがあったけど、意外と世の中の人は優しかったです。他の班を見ているとホワイトボードの前でああでもないこうでもないとずっと理屈をコネコネしているよりも、とりあえず作って見せていたところの方が円滑に進んでいるように見えたし、気持ち的にも楽しそうだったと思います。

何があっても美大生・芸大生がチームからいなくなるのを避けるべきだと思います。私が所属したチームはこの1年で芸大生が二人いなくなりました。まずなぜ彼らを失ってはいけないかについて考えを述べます。アイデア出しの場面では感性・感覚や視点が異なる学生がいる方がユーザーのインタビューに対して敏感になれるからです。私が感じたことのたとえ話ですが、日本語の「持つ」と英語での「have」というのは共有する意味があれど各々が持つ意味が完全に一致するわけではありません。ちょうどベン図の真ん中が重なるようなイメージです。各々にしかない表現や意味がある事は皆感じたことがあると思います。美大生の考え方やアイデアに対して持った私のイメージはこのようなものです。プロトタイプやスライド作成においては彼らの持つデザインの知識と経験が存分に発揮されます。自分たちのプロダクトを振り返った際に、もし彼らがいたらどうなっていたかなと思うと彼らを失ったことが悔やまれます。次にどうすれば彼らの脱退を防げるかという点について話します。注意してほしいのは美大・芸大生をデザインの業者のような目的だけで頼ることは間違っているという点です。彼らの持つ価値はそのような目先のテクニックではなく、異なる視点を持つという事を早めに認識することが大事かなと思います。そうすれば尊敬が生まれ、喧嘩が起きたとしてもチームからいなくなるという事は無くなるのではないかと思います。芸大生・美大生を軽々しく扱う東工大生がちらほらいるように感じたため書きました。

It is better to make slide in english even speak in japanese.

私のチームは他のチームと比べて苦労は少なかったと思います。その経験から1点だけアドバイスします。プロトタイプ・最終プロダクト作りは早めにすること。終盤で苦労していたチームは機械系でものづくり経験のある人がいない（少ない）チームでした。チーム構成がそうなってしまうのは別にいいと思います。電子工作であればググれば誰でもできます。私もすぐググります。ただ、経験が少ない人ほどものづくりにかける時間を短く見積もりがちです。時間がなければできるものもできません。十分時間をとって早めに行動してください。

取り組んでいる問題について，誰がどう困っていて，どう解決するのか，を常に文字化しておき，毎回の発表で触れる．対面で会えるテスト相手がなかなか見つからない場合は，紙芝居や動画を作ってメール等で送ることを考えるとコメントは増える．発達障碍で言うリタリコのコミュニティのような掲示板サイトは同じ人と何度もやり取りできる可能性があるという点でアンケートフォームより優れている．Slackは消えるので、インタビュー結果や検討の記録は別途記録しておく．

インタビューで多くの事実，特に自分たちが知らない事実を集めることとテーマを忘れないこと

とにかくホワイトボードに言葉と図を書きながら議論をすること。声だけでの議論(空中戦)はすぐに新たな発想が浮かばなくなって収束していってしまうし、何について話しているのかも分からなくなる。そして、さらには文章や図の２次元の要素ではなく、どんどんモノをつくって３次元空間に議論を持ち込むと、体験やロールプレイングが可能になり、浮かんでくるアイデアの数が爆発的に増える。というテクニック的なところも大事だと思うが、それよりなにより、すべてに先んじて優先されるべきなのは、相手の存在価値を奪わないこと。相手の意見を尊重するなどといった基本的な対人力がとにもかくにも複数人数で力を合わせるときには大切なことだなと思った。

ユーザーテストは適当にこなさないこと、テストで何を検証するのかしっかり考えること。プロトタイプ製作はすぐつくること。最終プロダクト製作には充分な期間を持って製作すること。

発案・検討が苦手な人はひたすら手を動かしてサイクルを回すことを正義と考えて取り組んでほしい。慣れている人は共通認識を持つためにエンジニアリングデザイン思考という“共通言語”を使いこなしてほしい。ザワザワするという感覚をそのまま使い続けるのではなく、適切に言語化して深掘りすることを諦めないでほしい。曖昧さと踊るのはそこじゃない。わかんないけどやってみる、やってみて見えたことはちゃんと明確にする、それが大事だと思う。「考えてもアイデア出なかった」ではなく、何を考えて煮詰まったのかをおしえあうべき。この授業はそういうプロセスを受け入れる態勢があると思っている。

後期いっぱいを共に過ごすチームメンバーの選び方がとても重要だと思います。自分の興味があるテーマも大事だと思いますが、それ以上に話し合いや考え方の伝え方など、チーム活動について考えることの多い授業で、とても悩ましかったです。話し合いができるのか、協調性はあるか、穏やかか、などの視点でチームを選ぶことを勧めます、と強く伝えたいです。また、せっかく美大生と同じ授業で課題に取り組んでいるにもかかわらず、あまり交流ができなかったことを後悔しています。積極的にコミュニケーションをとることを勧めたいです。

For next year students in general, I recommend to find the good insights as soon as possible and then focus on how to make prototype from them. The second thing is the purchasing, some parts could come early after 2-3days, but some can take a week, so make sure to count the delivery time and have spare time for it. For next year international students, this class provides a good approaching to the design thinking and the chance to do a real project with financial support. However, to deeply understand all, and to not become an outsider in the class, Japanese is definitely needed.

ものをつくる楽しさを持って取り組んで欲しいと思います。インサイトやコンセプトを考えるだけじゃなく、つくって気づく事をどんどん発見して欲しいし、何かものをつくる事自体を好きになってもらえると楽しいのかなと思いました。

いっぱい作りましょう

If you're not good at Japanese, it's better to think about how you can engage in discussions and how you can communicate with business.

部屋で答えのない会議を続けるよりも段ボールや粘土でもいいので早めに物作りを始めて、形をメンバーに共有することでユーザーのシナリオを洞察していった方がいいと思います。また枝葉末節にこだわりすぎるのではなくてまずはデザインプロセスが自分たちの課題にどのように活かせるのか、活かせないのかを巨視的に捉えた上で、チームの一員としての自分の役割を考えて行動すると、良い結果が出やすいと思います。

EDP-Bでもプロトタイプを作りこんだ方が良いです。

まず受け身じゃなくて、デザイン思考の本をちゃんと読んで自分の武器にすること。その為に他のマーケティング手法とは何が違うのか、自分で勉強すること。デザイン思考基礎では、最終的にここまで足を動かしてデザイン思考のサイクルを回すとは思ってもなかったので、グループメンバーが主体的動かなければいけない。その為には個人個人がデザイン思考を自分のものにする必要があると思う。

とりあえずモノを作った方がいいと思います．先生方もよく言われることだと思いますが，やはりちゃんと動くモノがないと，どんなに良い案でもユーザーからの意見は中途半端なものになる可能性が高いです．完璧なものでなくていいので最低限の機能が実演できた方が良いと思います．プロダクト案と比べてもフィードバックの雰囲気から異なったと感じました．

インタビューはやみくもに量をこなすよりも、その場その場でざわざわしたことに対して追加質問をして質を高めた方が効率的である。メンバー各々が欲しいものを考えるのではなく、ユーザーに寄り添って考えないとユーザーの心には刺さらない。みんなM1で終盤は忙しいので、EDP-Bのときからアクセル全開でプロトタイプ作成くらいまで行っておいた方が良い。チームが分裂しないためにもチーム内で分かれずにみんなで仲良くやった方が良い。

本音で言い合おう、ブレイクスルーしようとかチーム外の人はいうが、実際に本音を伝えるメンタリティが大事とかいうわけではない。本音を言える環境作りが大切。EDPでは（多分今後の社会でも）メンバーを選ぶことができないし、実際にチームを機能を低下させる人もいるから上手くいかなくても思い悩まなくていいと思うが、できる範囲での努力を行い、自身の学びを大きくしてほしい。

意見を戦わせることは大事だとは今回学びましたが、他の班を見ているとただ戦えばいいというものでもないと思いました。自分がなにが得意なのかといったことをしっかり考え、チームにとって自分ができることは何かを常に考えると、良い方に向かっていくと思います。頑張ってください。

社会人のEDP受講生向けに書きます。私がずっと大事にしていたのは、社会人だからといって、一歩ひいた立ち位置での議論参加・チーム活動をしないこと、学生に遠慮をしないことでした。他のメンバと同じ目線で進めることで自身のレベルアップ、特に当事者意識の醸成度合いが違うと感じています。一方、学生からみると社会人学生の発言は、影響力・納得感が強く聞こえることもあるようでしたのでそこは難しい課題です。(学生側の課題なのかもしれません。本当はもっと学生と議論をぶつけて、学生ならではの視点をもらいたかったです。チームの東工大メンバは活動意識が低く、自分の意見を持っていないことが多かったので、自分立ち位置や発言量、チームファシリテーションに苦悩しました)。

Japanese Language skill is strongly recommended in this course. Getting used to the way of thinking and communication in a Japanese style is important. As there will be chances to work with Japanese mentors, there will be possibility that the mentors are strict with Japanese way of communication and manners. Usually, international students will feel confused and frustrated without the experience of deep communicating with Japanese workers. Last but the most important, making sure the purpose and motivation of taking this course is essential. This course requires participants devote great efforts and time into it. And even devoted like that, student may not get any positive feedback or judgement. It would be better to make sure the content and process of the course and evaluate the risk of taking it.

I think my advice for people who are going to attend the EDP course next year is to do a more deep investigation in the beginning of the project. And put a lot effort in truly understand users during the interviews. This because only when the team can truly understand the problem they need to solve can they deliver good product that people need. Secondly, the team building is also the key to lead a successful outcome. The communication not only need to be fully understood between students but also mentors from the company.

モノを早く作った方が良いというのは本当に納得で、作りながら考えるということに加えて、後から見返したときにモノがあるのとないのではだいぶ違うと思う。また、最初の方に思いついたことは意外と良いことがあり、あとからでも振り返って考えてもいいと思う。また、技術的なところでは簡単なものでもプログラミングが出来ると役立つことは多いと感じた。チームビルディングとしては、最初から言いたいことは溜めずに言っていくことで衝突もあるが、後々上手くいくとおもう。

初期段階のインタビューから生まれたアイデアについて先生方からツッコミが入ったりするかもしれないけれど、よほどのことがない限りは自分たち班員の決定を重要視してプロトタイプに取り掛かってほしい。アイデアの練り直しは講義外でもできるが製作活動は実際に話し合いながら出ないと難しい。あと、講義外からの意見を求める時に実物があった方が絶対良質な意見が手に入る。

授業だからと思わず、仕事もしくはインターンだというモチベーションでグループワークに臨んだほうがいい。この授業に真剣に臨まなければ、ESDコースに所属した意味はない。

EDPは多くのことを学ぶ事ができる最高の授業です。いろんな壁にぶつかると思いますが、周りには素晴らしい人達がたくさんいます。先生方もみんなすごく個性的で、親切にいろんなことを教えてくれますし、ときには一緒に頭を抱えてくれます。TAの人たちは、私達のためにいろんなことを準備してくれます。物品だけでなく、心和むアイスブレイクや飲み会、デザイン思考の先輩・同じ経験をした先輩として優しいアドバイスもくれます。そして、なにより仲間を大切にしてほしいです。半年一緒に過ごすという時間はそう簡単には手にはいりません。そんな中で、相手のいいところをじっくり見ることができ、吸収できることも本当に稀な機会です。ぜひ、すべての時間を今としてしっかり受け止めて最高のEDPにしてください！

EDPツールキットを活用し、EDPの本をしっかり読んで書いてあることを実践してみて欲しい。（インタビューやユーザーテストでシチュエーションにこだわる等）EDP-BCは守破離の離ではあるが、今年は特になのか、自由にやりすぎた感がある。

1日でも早く、“機能を実装しているプロトタイプを作る”ことを勧める。議論ばかりしても、ユーザーの抱えている真の問題を知ることができず、実際に使ってみてもらって初めて理解の足がかりを掴むことができる。また、実際に動く「モノ」があることで、メンバー間の方向性を統一することができ、デザインプロセスのサイクルを回す効率を格段に高めることができる。早い段階なら失敗しても何も問題はないから、恐れずにどんどん作って欲しい。また、予算は思っているよりも多いから、プロジェクトが始まってからすぐにどんどん使っていくべきだと思う。

東工大生は感情はないが、好奇心と地雷はある、ということを踏まえて参加するとうまくいくかも。自分のことをたくさん話す（自己紹介ポートフォリオ必須）。できるだけ素直でいる（帰りたいとかつまんないとか言ってオーケー）。笑顔でいる（伝染するから）。

知らない人にインタビュをとにかくたくさんしよう．

グループワークの最初にはチームビルディングに時間を多めに割いてほしい。実際に起こった問題の中で最も多かったものはチームワークによるものだったと思うし、チーム内で同じ目標を持ってそこに向かって行かなければ、本当に良いモノは作れないと感じた。また周りの意見を聞くことは大切であるが、全ての意見に耳を傾けすぎない方が良いと思う。そうしてしまうと、軸がぶれてしまい、何をしたいのかわからないモノができてしまう。しっかりとした軸を持ち、取捨選択をきちんとチームメンバーで考えて、楽しく良いモノを作ってほしい。

# Staff

## Instructors

Saito, Sakamoto, Kado, Yagisawa, Terui, Park, Inaba, Hijikata

## Teaching Assistants (TAs):

Yuma ITO, Yosuke TAJIRI, Randy Raharja

# Corporate Partners

* ATC株式会社 / ATC Co., Ltd.
* パナソニック株式会社 / Panasonic Corporation
* 株式会社ウェザーニューズ / Weathernews Inc.
* 株式会社リコー / Ricoh Co., Ltd.
* さくらインターネット株式会社
* エイベックス株式会社
* フォントワークス株式会社
* 太陽ホールディングス株式会社
* 株式会社オロ

# Schedule

## [EDP-B1] September 29, Sat., 10:00-15:50

1. [10:00-10:30] ガイダンス
   - EDP-B/Cの概要、スケジュール、評価方法
2. [10:30-12:15] パートナー企業によるテーマ説明
   - 105分で9社 ... 1社あたり11分程度
   - プレゼン（3〜5分） + 質疑応答（5〜7分）：合計10分
   - 各自希望票（5つくらいまで？）を提出してからお昼へ
   - ※パートナー企業の皆様は「7.プロジェクト計画」開始時に戻ってきてください
3. [12:15-13:20] お昼休憩
4. [13:20-14:00] チーム編成
   - DTF + EDP-A で貢献度が高かったメンバーを中心にチームづくり
   - 上記の希望票を参考にすること
   - 欠席者の存在を考慮すること
   - 英語チームの存在を考慮すること
5. [14:00-14:45] EDP-B/Cの進め方
   - チーム名の決定
   - Slackの準備
   - 予算の使い方
   - パートナー企業とのコミュニケーション
   - ユーザーリサーチの進め方
   - 次回までの宿題
   - （時間があれば）チームビルディングのアクティビティ
6. [14:45-15:00] 休憩
7. [15:00-15:50] プロジェクト計画
   - パートナー企業と必要な情報（e.g. テーマを設定した背景、プロジェクトに対する期待値、ユーザーリサーチの対象と実施方法など）を共有し、今後の進め方を決めてください
   - その後、時間いっぱいまでグループワーク
   - ふりかえり

### Homework:

Have interviews with the potential users (at least five users per team) of a product which you will develop.

1. Make a list of questions
2. Write interview notes (transcription)
3. Take more than three photos per interview
  * Continue until your team finds at least three strange/interesting/surprising episodes.
  * Save the files somewhere and submit the links to `Slack#homework-20180929` (before the next lecture)
  * Print and bring them to the next lecture.
4. In the next class, you should give a 5 min presentation:
  * Y (yattakoto): what your team did
  * W (wakattakoto): what your team learnt
  * T (tsugiyarukoto): what your team will do
5. Make sure also to create "Skill Matrix" and read "Google re:Work" as a homework.

## [EDP-B2] October 13, Sat., 10:00-15:50

- 10:00-10:30: Guidance
    - Introduction of new members
    - Create your name tag
    - Icebreak "Feedback BINGO" (by Itoh)
- 10:30-12:15: Presentations about User Research
    - 10min per team:
        - 3~5min Presentation
            - Yattakoto: what you did
            - Wakattakoto: what you learnt
            - Tsugiyarukoto: what you will do next
        - 5~7min Feedback
- 12:15-13:25: Lunch Break
- 13:25-13:35: How to purchase things (by Tajiri)
- 13:35-13:45: Announcement of Homework
    - Previous Homework
        - Psychological Safety and Dependability
        - Summary of Skills Training Matrix
    - Design your design process and draw a few product sketches (using [EDP template](https://titech-edp.github.io/toolkit/product-sketch.pdf))
    - Give a 10 min presentation in the next class:
        - 3~5 min for presentation
            - design process (you've already done)
            - product skeches
            - design process (you'll do next)
        - 5~7 min for feedback
    - Save the slide somewhere and submit the link to `Slack#homework-20181013` (before the next lecture)
    - **FYI: standard design process:**
        - Do a lot of user interviews and observations
        - Create a user-journey-map and find some interesting points
        - Create at least three POVs (using the form of tatemae or extreme users)
        - Create at least three HMWs per POV.
        - Create at least three Design Principles from the HMWs.
            - [![Image](https://gyazo.com/a2de351cc9695ef3eb481c4c3838108f/thumb/1000)](https://gyazo.com/a2de351cc9695ef3eb481c4c3838108f)

        - Select one Design Principle and the relative three HMWs, and for each HMW do sketch using [10-plus-10 method](http://saul.cpsc.ucalgary.ca/sketchbook/wp-content/uploads/Chapter-1.4-10Plus10Method.ppt).
        - Categorise the final three sketchs into "Favorite", "Rival", and "Dark Horse".
        - Here are the best three ideas/skeches 😄
- 13:45-14:45: Group Work (1)
- 14:45-14:55: Break
- 14:55-15:40: Group Work (2)
- 15:40-15:50: Reflection
    - KPTS on Post-it
        - (Your Name)
        - Keep (Good Things for you/team)
        - Problem (Bad Things for you/team)
        - Try (Improvements for you/team)
        - Suggestion (for the lecture)
    - Then take a photo as a team and submit it to `Slack#realtime-20181013`.

## [EDP-B3] October 27, Sat., 10:00-15:50

-  10:00-10:30: Guidance
    - Icebreak by TA
    - Create your name tag
    - Create a list of your team members (for the attendance check)
    - Decide the order of presentation
-  10:30-12:15: Presentation
    - 10min per team:
        - 3~5min Presentation
            - design process (you've already done)
            - product skeches
            - design process (you'll do next)
        - 5~7min Feedback
-  12:35-13:45: Lunch Break
-  13:45-14:00: Mini Lecture by Kado
    - 🚧 Problem: "Regular Facilitator"
        - [![Image](https://gyazo.com/91768df9c51e76b2750eeb2c27d7c47d/thumb/1000)](https://gyazo.com/91768df9c51e76b2750eeb2c27d7c47d)
        - source: [https://hbr.org/2012/04/the-new-science-of-building-great-teams](https://hbr.org/2012/04/the-new-science-of-building-great-teams)
    - Summary of Fedback Bingo
    - Feedback of KPTS on EDP-B2
    - 📝 Homework:
        - Take a survey to explore **viability**.
            - Goal: Take a few steps away from current ideas and get a new perspective.
            - e.g. 9-window-tool, 2x2 matrix, analogous inspiration, field research, expert interview, or so.
                - You can select your favorite methods. 😊
        - After that, create new prototype(s) and draw storyboard(s) to check **feasibility**.
        - Save a slide somewhere and submit the link to `Slack#homework-20181027` (before the next lecture)
    - Announcement of EDP-4 (2018-11-10):
        - Give a short presentation about what you've done, prototype, and storyboard:
            - 3~5 min Presentation:
                - what you've done to get a new perspective
                - prototype(s)
                - storyboard(s)
                - what you will do
            - 5~7 min Feedback
    - Announcement of EDP-5 (2018-11-24):
        - Interim Presentation:
            - Give a 3 min. pitch about your solution
            - Give a 3 min. skit with your best prototype, which expresses user-experience vividly
            - Give a 3 min. presentation including:
                - reflections of your design process and what you’ve learned in EDP-B
                - plans for further works in EDP-C
            - Take 3 questions at most from the audience
-  14:00-15:40: Group Work
-  15:40-15:50: Reflection
    - NEW FORMAT!! Create this **as a team**:
        - [![Image](https://gyazo.com/9aa4b115cbf39e014d4334014eb122f7/thumb/1000)](https://gyazo.com/9aa4b115cbf39e014d4334014eb122f7)
    - Then take a photo as a team and submit it to `Slack#realtime-20181027`.

## [EDP-B4] November 10, Sat., 10:00-15:50

- 10:00-10:30: Guidance
    - Take your name tag
    - Icebreak by TA (Randy)
    - Decide the order of presentation
- 10:30-12:15: Presentation
    - 3~5 min Presentation:
        - what you've done to get a new perspective
        - prototype(s)
        - storyboard(s)
        - what you will do
    - 5~7 min Feedback
- 12:15-13:20: Lunch Break
- 13:20-13:30: Mini Lecture by Kado
    - Are these Tokyo-Tech Specific (therefore Useless) Methods?
        - Short answer: Absolutely NOT.
            - Design Thinking is relatively new method , not well defined, and not widely spreaded yet.
            - They are not Tokyo-Tech specific (see below).
                - Many companies and ex-students are using our methods.
        - Encourage to google in ENGLISH!! ( Tokyo-Tech has dominated search results in Japanese 🙄 )
            - [![Image](https://gyazo.com/bda8b482922d0f21349ccaa45070a038/thumb/1000)](https://gyazo.com/bda8b482922d0f21349ccaa45070a038)
        - IMPORTANT: We are interested in not ”Design Thinking" methods but rather "Engineering Design" methods.
        - Originally, Saito-sensei was a visiting researcher of Stanfod and he brought its ME310 and d.school design methods to EDP.
        - Tokyo-Tech and IDEO Tokyo created the initial educational materials for "Design Thinking Fundamental" course.
        - Why Stanford and IDEO?
            - [![Image](https://gyazo.com/00d1d9b527986a371380b3b2c5005b48/thumb/1000)](https://gyazo.com/00d1d9b527986a371380b3b2c5005b48)
                - cf. [https://speakerdeck.com/kdmsnr/tokyo-tech-dtf-2018-introduction?slide=16](https://speakerdeck.com/kdmsnr/tokyo-tech-dtf-2018-introduction?slide=16)
                - cf. [https://medium.com/titech-eng-and-design/e8ef02195fbe](https://medium.com/titech-eng-and-design/e8ef02195fbe)
        - Every year, the faculty team is improving the materials in accordance with the situation of EDP .
            - Especially Tokyo-Tech students are not good at creating POVs. 🤔
            - ASIDE: I (Kado) DO NOT LIKE affinity-diagram and brainstorming both are famous for "Design Thinking". 😣
        - We know that "Referenceability" matters. 🔎
            - [![Image](https://gyazo.com/ff7e271d660bda7de1b436eeea1c0e61/thumb/1000)](https://gyazo.com/ff7e271d660bda7de1b436eeea1c0e61)
            - EDP-Toolkit: [https://titech-edp.github.io/toolkit/](https://titech-edp.github.io/toolkit/)

    - DESIGN YOUR DESIGN RPOCESS !!
        - We think our methods are NOT the best or one-fit-all perfect one.
        - There are various kinds of themes in EDP-B/C.
        - So, we encourage you to "Design Your Design Process" specific to your theme.
            - 守破離（DTF, EDP-A, and EDP-B/C <- now here)
        - Double Diamond:
            - EDP-B is for "define strategy" and EDP-C is for "execute solution"
            - [![Image](https://gyazo.com/cb0d7b5757732e01367ed25f3971bdd9/thumb/1000)](https://gyazo.com/cb0d7b5757732e01367ed25f3971bdd9)
            - source: [https://www.thoughtworks.com/insights/blog/double-diamond](https://www.thoughtworks.com/insights/blog/double-diamond)
    - As I've mentioned millions of times, R-E-A-D "Google re:Work"
        - ja) [https://rework.withgoogle.com/jp/subjects/teams/](https://rework.withgoogle.com/jp/subjects/teams/)
        - en) [https://rework.withgoogle.com/subjects/teams/](https://rework.withgoogle.com/subjects/teams/)
    - Announcement of EDP-B5
    - 📝 Homework:
        - Prepare for the Pitch, Skit, and Presentation (Design Process and Plans for EDP-C)
        - Pitch Template (cf. [The YC Seed Deck Template](https://blog.ycombinator.com/intro-to-the-yc-seed-deck/)):
            - Slide0 (Title):
                - Product Name and/or Slogan
                - Photo of your Prototype
                - Desgin Prompt
                - Corporate Partner
                - Team Name
                - Team Members
                - Date
            - Slide1: Problem
            - Slide2: Solution
            - Slide3: Unique Insight
            - Slide4: Voice of User
            - Slide5: Future Works
            - Slide6: What we need
        - Tips for the pitch:
            - You can insert the skit before or after slide2, if you want.
            - You should not use design thinking jargon (ex. POV, HMW, or so)
        - Skit template: None
        - Presentation template: None
        - Save a slide somewhere and submit the link to `Slack#homework-20181110` (before the next lecture)
- 13:30-14:30: Group Work (1)
- 14:30-14:40: Break
- 14:40-15:40: Group Work (2)
- 15:40-15:50: Reflection
    - Create this as a team:
        - [![Image](https://gyazo.com/9aa4b115cbf39e014d4334014eb122f7/thumb/1000)](https://gyazo.com/9aa4b115cbf39e014d4334014eb122f7)
    - Then take a photo as a team and submit it to `Slack#realtime-20181110`.

## [EDP-B5] November 24, Sat., 10:00-15:50

- 10:00-10:15: Guidance
    - Take your name tag
    - Announcement of NDA
    - Change layout
    - Decide the order of presentation
- 10:15-12:15: Interim Presentation (12min. * 9 teams + break:10min)
    - Give a 3 min. pitch about your solution
        - Use the pitch template (see EDP-B4)
    - Give a 3 min. skit with your best prototype, which expresses user-experience vividly
    - (↑real scenes)
    - (〰〰〰draw a clear line〰〰〰)
    - (↓behind the scenes)
    - Give a 3 min. presentation including:
        - reflections of your design process you've done and what you’ve learnt in EDP-B
        - plans for further works in EDP-C
    - Take 3 questions at most from the audience
- 12:15-13:20: Lunch Break
- 13:20-13:40: Lecture by Saito-sensei
- 13:40-14:00: Homework and Deliverable
    - Homework:
        - Complete 100 tests by the end of EDP-C
            - It depends on you that how to count "test".
        - Preparing for the next presentation (5min.)
            - At first, tell us how many times you've tested since the last class and the total number of tests you've ever done.
            - Then, DEMO (prototype and/or experience) + YWT (Yattakoto, Wakattakoto, and Tsugiyarukoto)
            - Save a slide somewhere and submit the link to `Slack#homework-20181124` (before the next lecture)
    - Deliverables:
        - Slide (already done)
        - Report: [https://goo.gl/forms/kATdSeS8p9M2VNLs1](https://goo.gl/forms/kATdSeS8p9M2VNLs1) (Due date: 2018-11-30 24:00)
    - Final Presentation:
        - Pitch, Movie, and Design Process
- 14:00-15:50: Group Work
    - Team Journey Map
    - [![Image](https://gyazo.com/f0461048e8c76a59c7bebe3e222ee56e/thumb/1000)](https://gyazo.com/f0461048e8c76a59c7bebe3e222ee56e)
    - Kudos Card
    - Planning for EDP-C

#### 懇親会

* Date : 11/24 17:00-19:00
* Place : もつ鍋らく 大岡山本店（Motsunabe Raku）

#### パートナー企業向け意見交換会
- 12:15-12:30 and 16:00-16:15（実際：12:35-13:00 and 16:00-16:40）
- チームの状況
- テーマの忠実度
- メンタリングの方針
- 最終発表会では講評をいただく

## [EDP-C1] December 8, Sat., 10:00-15:50

- 10:00-10:30: Guidance
    - Take your name tag
    - Icebreak (paper tower) by Ito
    - Decide the order of presentation based on score of the icebreak
- 10:30-12:15: Presentation
    - 今回からはプレゼン5分で打ち切り!!
    - 5 min Presentation:
        - At first, tell us how many times you've tested since the last class and the total number of tests you've ever done.
        - Then, DEMO (prototype and/or experience) + YWT (Yattakoto, Wakattakoto, and Tsugiyarukoto)
    - フィードバックのやり方を変えたい。。。
        - （結論）3チームずつ連続で発表 → 10分で教員からのフィードバック + 各チームのチャンネルに感想を書き込み
- 12:15-13:20: Lunch Break
- 13:20-13:50: Mini Lecture
    - テストの回数を出してることからもわかるように、作ってテストするのを100回繰り返して欲しい
    - あと4回しか講義がないから早く作り始めよう
    - 企業からもらったテーマがよくわからない場合は再定義するのもアリ
        - 発表の際に「再定義しました」って言ってもらえればよい
    - EDP-Bではチームに閉じていたが、Cではもっとオープンにやってほしい
        - 飲み会でチーム間でメンバーのトレードはどうか？という話が出ていたが……それはさすがに大変なので、他のチームとかに行ってみるのもアリ。まるでメンバーかのように振舞ってみたりスカウトするのもアリ。ただし、自分のチームとのバランスは取ること。
        - アイデアのパクりパクられも推奨する「このクラス内では何を盗んでも構わない」
    - 過去の知見を得たいならEDPの本を読もう
    - Dance with ambiguity
    - プレゼンも「なんか面白いものがあるんですけどどうでしょう」みたいなのでもよい
    - 作ってから考える
    - 作ってから寸劇してみる
    - 1アイデア1コント
    - 座って会議ばかりより立ち上がっていろんなことをやってほしい
- 13:50-15:40: Group Work
- 15:40-15:50: Reflection
- Homework: Submit a slide to `Slack#homework20181208`

## [EDP-C2] December 22, Sat., 10:00-15:50

-  10:00-10:30: Guidance
    - Take your name tag
    - Icebreak by TA
    - Decide the order of presentation
-  10:30-12:15: Presentation
    - 5 min Presentation * 3 teams successionally:
        - At first, tell us how many times you've tested since the last class and the total number of tests you've ever done.
    - 10 min feedback + 5 min writing it down on the Slack
        - ref.  previous comment:
        - > フィードバック書いてるときに、お話を聞くのはだいぶ難しいなとおもいました
            >> ちょうど15分余ったので、10分コメント+5分フィードバック書き込みの時間、にしますかね。ちょっと場が沈黙になりそうなのが不安ですけども。
-  12:15-13:20: Lunch Break
   - ミーティング：team-popeye
-  13:20-13:50: Mini Lecture
    - 宿題出し忘れてた件。。。まあ、毎回おなじ要領でやってください。
    - ユーザーテストが全体的に浅い気がする → もっと「深い・長い」ユーザーテストを
    - オープンなコミュニケーションの利点
    - （大事なことなので2回め）はやく「プロダクト」を作り始めよう！
    - EDP-C5 でLTやろーぜー。1人3分くらいでEDPについて自由に語ってもらいたい。
        - その内容をブログに書いてくれるともっと嬉しい。（加点しちゃいそう）
    - HRT matters in this class.
    - Final Presentation and Project Document (IMPORTANT!!!!)
    - https://speakerdeck.com/kdmsnr/2018-edp-bc-final-report-announcement
        - Report Template:

```
https://titech-edp.github.io/2018-edp-bc/2018_EDP-BC_Final-Report_(teamname)_JA.dotx
https://titech-edp.github.io/2018-edp-bc/2018_EDP-BC_Final-Report_(teamname)_EN.dotx
```

- 13:50-15:40: Group Work
- 15:40-15:50: Reflection
- Homework: Submit a slide to `Slack#homework20181222`

## [EDP-C3] January 12, Sat., 10:00-15:50

- 10:00-10:30: Guidance
    - Take your name tag
    - Icebreak by TA (Randy): Find similarities
    - Decide the order of presentation
    - 席替えしようぜ！
- 10:30-12:15: Presentation
    - 5 min Presentation * 3 teams successionally:
        - At first, tell us how many times you've tested since the last class and the total number of tests you've ever done.
    - 10 min feedback + 5 min writing it down on the Slack
- 12:15-13:20: Lunch Break
    - ミーティング：team-千歯コキ
- 13:20-15:40: Group Work
- 15:40-15:50: Mini Lecture by Kado + Reflection
    - 「Presentation Checklist（発表チェックリスト）」作ったよ
    - Check Final Presentation and Artifacts
    - 最終発表会の告知ページを出したい
        - 最終発表会の発表順を決めたい
        - チームの紹介文がほしい
        - パートナー企業の発表者のお名前がほしい
    - （そういえば、モノを作るのが苦手なチームがある？）
- Homework: Submit a slide to `Slack#homework20190112`

## [EDP-C4] January 26, Sat., 10:00-15:50

- 10:00-10:30: Guidance
    - Take your name tag
    - Icebreak by TA
    - Decide the order of presentation
- 10:30-12:15: Presentation
    - 5 min Presentation * 3 teams successionally:
        - At first, tell us how many times you've tested since the last class and the total number of tests you've ever done.
    - 10 min feedback + 5 min writing it down on the Slack
- 12:15-13:20: Lunch Break
- 13:20-13:50: Mini Lecture by Kado
    - 次回はLT！（通常の発表はナシ）ref. [https://en.wikipedia.org/wiki/Lightning_talk](https://en.wikipedia.org/wiki/Lightning_talk)
        - チームごとに1人3分ずつプレゼン
        - テーマは「EDPについて」。内容はなんでもOK。ネタに走ってもいいですが、みなさんの本音を知りたい。
            - ぜひブログも書いてね！（そのままの内容でOK。スライドを画像として載せるとよいです）
                - → [https://medium.com/titech-eng-and-design](https://medium.com/titech-eng-and-design)
        - 1台のマシンにメンバー全員のプレゼン資料を入れといてね
            - 無理にスライドをつかわなくてもいいです
        - パートナー企業の方もぜひぜひ（チームの次に発表してください。マシンは個人用でもOKです）
        - 順番は当日の朝に決めましょう
    - 最終発表当日の確認
        - Check 「Final Presentation and Artifacts」
        - プレゼンの練習を何度もやっておきましょう
            - See 「Pitch_Template」
            - 「動画」と「プロセス」のプレゼンも忘れずに
        - ブースの準備もしといたほうがいいです
            - 看板とか、ポスターとか、小道具なんかがあると便利（参考：去年の様子↓）
            - [![Image](https://et-cdn.shoeisha.jp/static/images/article/741/741_DSC_5370.JPG)](https://et-cdn.shoeisha.jp/static/images/article/741/741_DSC_5370.JPG)
            - 予算を使っていろいろ準備しといてください
        - 発表順はいまから決めておきたい
- 13:50-15:40: Group Work
- 15:40-15:50: Reflection

## [EDP-C5] February 2, Sat., 10:00-15:50

- 10:00-10:30: Guidance
    - Take your name tag
    - Icebreak by TA
    - Decide the order of presentation
- 10:30-13:20: Lightning Talks
    - 3 min Presentation
- 13:20-14:30: Lunch Break
- 14:30-15:00: Mini Lecture by Kado
    - LTおつかれさまでした
        - 途中で切れたやつは、ブログを書くとよいと思う！
    - 進捗どうですか？
        - 「OKです！」→ そのまま続けてください。
        - 「ダメです！」→ 相談しましょう。声かけてください。
    - 最終発表当日の確認（大事なことなので2回目）：
        - Check Final Presentation and Artifacts（💥 Deadline: 2019-02-17 24:00 💥）
        - プレゼンの練習を何度もやっておきましょう
            - See Pitch_Template
            - 「動画」と「プロセス」のプレゼンも忘れずに
        - ブースの準備もしといたほうがいいです
            - 看板とか、ポスターとか、小道具なんかがあると便利
            - 予算を使っていろいろ準備しといてください
        - 当日の予定：
            - 11:00 西9号館コラボレーションルームに集合 / The meeting place is W-9 Collaboration Room
            - 11:00-12:30 リハーサル / Rehearsal
                - プレゼンの時間確認 / Check the duration of presentation.
                    - 午前中に教員かTAに確認をもらうこと / Make sure to ask faculty or TA to confirm the duration.
                - 机の配置 / Desk layout
                - 電源など必要なものを確認 / Power strip etc. whatever you need
                - プロトタイプの設置 / Deploy the Prototype
                - ポスターや配布物のチェック / Poster and Brochure check
                - モニタの接続チェック（発表逆順に） / Monitor check (in the presentation order)
                    - 11:10 千歯コキ
                    - 11:15 nandarone
                    - 11:20 guardian
                    - 11:25 すぷりんぐ
                    - 11:30 シャンシャンFC
                    - 11:35 を
                    - 11:40 diversity
                    - 11:45 ぱんだ
                    - 11:50 ポパイ
                - お昼は適当に！ / Feel free to have a lunch anytime
            - 12:30 多目的ホールに移動 / Move to Multi-Purpose Digital Hall
            - 12:40 受付開始 / Open
            - 13:00 発表開始 / Presentation Start
            - 15:10- コラボレーションルームへ移動 / Move to Collaboration Room
            - 15:10-15:50 デモ / Demonstration
            - 15:50-16:15（→ 学生向け） ふりかえり / Reflection
            - 15:50-16:15（→ 協力企業向け） 懇談会
            - 16:15-17:45 懇親会 / Social gathering
- 15:00-15:40: Group Work
- 15:40-15:50: Reflection
    - 懇親会の参加者チェック


## [EDP-FINAL-PRESENTATION] February 9, Sat., 13:00-17:30

### 外部向け開催概要
→ [開催概要](./demoday/)
