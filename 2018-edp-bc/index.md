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


# Staff

## Instructors

Saito, Sakamoto, Takeda, Kado, Yagisawa, Terui, Park, Inaba, Hijikata

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
