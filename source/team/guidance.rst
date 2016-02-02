==================
 スタッフの手引き
==================

この文章は「PyCon JP 2016のスタッフをやろう」という人が実際にスタッフになって、なんらかのタスクをできるようにするための手順とかをまとめたものです。

PyCon JP 2016の目的と目標
=========================

目的と目標
----------
- プログラミング言語Pythonならびに関連するソフトウェアに関心を持つ者に対して、カンファレンス等の開催を企画・運営・支援することで、交流・啓蒙・普及・教育の場を提供し、日本および世界各国におけるPythonの普及と進化に寄与します。

  - `一般社団法人 PyCon JP 設立のお知らせ — PyCon JP <https://www.pycon.jp/committee/foundation.html>`_ より
- PyCon JP 2016がPythonとユーザーが盛り上がる、レベルアップするきっかけになることを目標としています。  

行動規範
--------
- あとで書く
- ハラスメント行為ダメ絶対

スタッフ登録手順
================
1. `PyCon JP 2016スタッフ申し込み <https://docs.google.com/forms/d/15PNGpDGhnXVGsNk8jkcYsu2XpVEIqNHcM0L-ah-2aek/viewform>`_ フォームから申し込みをする
2. Slack(チャット)の招待メールが届くので、チャットに参加する(参考: Slack登録手順)
3. JIRA(課題管理)の招待メールが届くので、登録する(参考: JIRA登録手順)
4. PyCon JPフォルダへのアクセス権限が設定されるので、 **スタッフ名簿** に名前や連絡先等を書ける範囲で書く

チーム
------
メンバーは基本的にチームに所属してもらいます。
チームごとにどんなことやるかを以下に書いてあるので、どのチームに所属するかを決めて下さい。
不明点はSlackで聞いてください。

- 事務局

  - 全体がうまくまわるようにいろいろやるチーム
  - 参加者の管理、スポンサー、会計、グッズ制作、ガイドブック（紙）、受付、デザイン

- 会場

  - 物理的なものとかをとりまとめるチーム
  - 会場選定、備品管理、動画配信、ランチ、おやつ、Party、ネットワーク

- プログラム

  - PyCon JP会期中のコンテンツをまとめるチーム
  - キーノート、プログラム、チュートリアル、スプリント、オープニング、クロージング、オープンスペース、ポスターセッション、同時通訳

- メディア

  - 外部への宣伝とか情報を出す部分をとりまとめるチーム
  - Webサイト、Twitter、Facebook、宣伝LT、事前・事後の記事（CodeZine、gihyo.jp等）、PyCon JP Blog、PyCon Blog、Guidebook app

Slack(チャット)
===============
- http://pyconjp.slack.com/
- ヘルプページ(英語) https://pyconjp.slack.com/help
- メンバー間、各チームでの相談用のチャットです。ログは最新10,000件しか残らないので、記録したい情報はJIRA(課題管理)ツールを使用してください。

Slack登録手順
-------------
1. 管理者から招待されると招待メールが届くので、 **Join team** をクリックして登録画面を開きます。

   .. figure:: images/slack1.png
      :alt: Slackからの招待メール
      :width: 400

      Slackからの招待メール

2. 登録画面でユーザー名、パスワードを入力してSlackのアカウントを作成します。ユーザー名は「呼ばれたい名前」にしてください。発音が難しいIDなどはできるだけ使用しないでください。

   .. figure:: images/slack2.png
      :alt: Slackに登録
      :width: 400

      Slackに登録

3. `Edit Profile <https://pyconjp.slack.com/account/profile>`_ でプロフィール画像を設定します。顔と名前を一致させるために、顔のわかる画像にしてください。

   .. figure:: images/slack3.png
      :alt: プロフィール編集画面
      :width: 400

      プロフィール編集画面

Slackの基本的な使い方
---------------------
- `Download Apps <https://slack.com/downloads>`_ でMac、Windows、iOS、Androidなどのアプリが提供されています。使いやすいのでぜひインストールしてください。
- 参加するチャットルーム(channel)の管理(`Browsing and joining channels <https://get.slack.help/hc/en-us/articles/205239967-Browsing-and-joining-channels>`_ 、 `Leaving a channel <https://get.slack.help/hc/en-us/articles/201375146-Leaving-a-channel>`_)

  - channelに参加するには、参加したい channel をクリックして **Join Channel** をクリックします。
  - channelを抜けるには、channel名の横をクリックしてメニューから **Leave channel** を選びます。再度参加することも可能です。
  - 優先して参照したいchannelは、channel名横の **☆** をチェックすると上の方に表示されます。

- 通知(mention)(`Using @mentions <https://get.slack.help/hc/en-us/articles/205240127-Using-mentions>`_ 、 `Making announcements <https://get.slack.help/hc/en-us/articles/202009646-Making-announcements>`_)

  - メッセージに ``@ユーザー名`` と入力とその人にmention(通知)が飛びます。回答がほしいときなどはmentionを使用してください。
  - ``@here`` と入力すると、その部屋にいる現在アクティブな人に通知が飛びます。誰かに相談したいときなどに使うと便利です。
  - ``@channel`` と入力すると、その部屋にいる全員に通知が飛びます。
  - 発言の中に名前だけを入れたい場合は、 ``@`` をつけないで名前だけを書きましょう。(例: XXの件は takanory がやってくれたみたい→報告なのでmentionしない)

- メッセージのフォーマット(`Formatting your messages <https://get.slack.help/hc/en-us/articles/202288908-Formatting-your-messages>`_)

  - ``*アスタリスクで囲む*`` と **太字**
  - ``_アンダースコアで囲む_`` と *イタリック*
  - 最初に ``>`` をつけるとインデントされたテキスト(blockquote)
  - バッククォート(`````)で囲むと ``固定幅のフォント``
  - 3つのバッククォート(```````)で囲むと ``複数行で固定幅フォント``

- メッセージの編集と削除(`Editing or deleting messages <https://get.slack.help/hc/en-us/articles/202395258-Editing-or-deleting-messages>`_)

  - 自分が入力したメッセージをあとから編集、削除できます。
  - 直前のメッセージを編集、削除する場合はカーソルの ``↑`` を入力します。
  - 過去のメッセージの場合は、メッセージの上にカーソルを持っていくとメニューが表示されるので、そこをクリックして編集、削除ができます。

- Slackの使いこなしについては `Using Slack – Slack Help Center <https://get.slack.help/hc/en-us/categories/200111606-Using-Slack>`_ にいろいろヘルプがあるので参照してください。
