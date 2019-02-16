.. _environment:

============
 環境の準備
============

チームメンバーの募集をはじめる前に(または平行して)、チームを運営するための各種環境を用意します。

なお、PyCon JPではできるだけ自分たちではサーバーを持たず、外部のサービスを利用しています。
理由としては、サーバーそのものを運用する手間をかけたくないためです。

チャット
========
チームメンバー間でのコミュニケーションのためにチャットを用意します。

.. index:: slack

`Slack <https://slack.com/>`_ のチームを新規に作成しましょう。
Slackはさまざまな外部サービスとの連携(インテグレーション)が可能なので、後述するコード管理やタスク管理と連携できて便利です。

:他の選択肢: `HipChat <https://ja.atlassian.com/software/hipchat/>`_ 、
   メーリングリスト

タスク管理
==========
.. index:: JIRA

タスク管理の環境を用意します。
PyCon JPでは `JIRA <https://ja.atlassian.com/software/jira>`_ を使用しています。

JIRAは有料のサービスですがPyCon JPでは
`Open Source License Request <https://ja.atlassian.com/software/views/open-source-license-request/>`_
からライセンス要求を出し認められたため、無料で使用しています(ありがたいです)。

:他の選択肢: `Redmine <http://redmine.jp/>`_

ドキュメント管理
================
.. index:: Googleドライブ

ドキュメント管理は
`Google ドライブ <https://www.google.co.jp/intl/ja/drive/>`_
で行います。
フォルダをスタッフに共有し、ドキュメントはすべてそのフォルダに入れるようにします。

Google ドライブはスプレッドシートは非常に便利ですが、ドキュメントはさくさく書ける感じではないので他のツールも考えた方がいいかも知れません。

:他の選択肢: `Confluence <https://ja.atlassian.com/software/confluence>`_ 、
   GitHubのWiki、 `esa.io <https://esa.io/>`_ 、
   `DocBase <https://docbase.io/>`_ 、Wikiなどなど

コード管理
==========
.. index:: GitHub

github の organization を作成します。
このorganization には基本的にスタッフを全員入れて、書き込み権限を与えます。

githubで管理する情報としては以下の様なものが考えられます。

- サイトのソースコード
- ドキュメント
- タスク(後述します)

githubのissue機能はあまり強力ではないので、本格的なタスク管理を行いたい場合には別なサービスの利用をおすすめします。

- 参考: `Creating a new organization account - User Documentation <https://help.github.com/articles/creating-a-new-organization-account/>`_
  
:他の選択肢: `Bitbucket <https://bitbucket.org/>`_ 、
  `GitLab <https://about.gitlab.com/>`_

お金管理
========

銀行口座
--------
イベントのお金を管理するために銀行口座を作成します。
`ジャパンネット銀行 <http://www.japannetbank.co.jp/>`_
が `任意団体(サークル等)の名前で口座を開設 <http://www.tecking.org/archives/3589>`_ できるようなのでおすすめです。

ジャパンネット銀行が便利な所

- 振り込みにトークンが必要なので、会計担当がトークンを持てば安心
- トークンを追加可能(振り込み担当を複数人とかもできる)
- デビットカード番号が発行できるため、カード決済も可能。カードレスVisaデビットだとカード番号を一時的に発行して捨てることもできる

  - 参考: `商品概要｜Visaデビット <http://www.japannetbank.co.jp/service/payment/cardless/detail.html>`_

:他の選択肢: `株式会社ゆうちょ銀行 <http://www.jp-bank.japanpost.jp/>`_

.. _paypal:

PayPal
------
.. index:: PayPal
           
イベントのチケット販売したお金を受け取るために `PayPal <https://www.paypal.jp>`_ の口座を用意します。
支払いを受け取るためには `ビジネス向けアカウントを登録 <https://www.paypal.jp/cms/templates/jp_3rd_global_side.aspx?pageid=10737418282>`_ する必要があります。

書類のやりとりなどがあって多少面倒ですが、ビジネス向けアカウントがあるとイベント登録サイトの connpass で前払いのイベントの作成ができます。

PayPalでは、1つのアカウントに複数の「メールアドレス」を登録出来ます。connpassのpaypal設定にそれぞれのメールアドレスを使用することで、PayPalの履歴で何の支払か見分けられるようになります（利用例: :ref:`event-registration-on-connpass` ）。メールアドレスを用意するために、Google Groupを作成して、そのアドレスをPayPalのメールアドレスに設定します。設定は一社の会計担当が行います（PayPalログイン -> アカウント設定 -> 事業情報 -> メールアドレス）。

PayPalの1つのアカウントには、複数のユーザーを追加できます。追加ユーザーにはパスワードと権限を個別に設定できます。現在は「PyCon JP イベント」「会計事務所」ユーザーがあります。設定は一社の会計担当が行います（PayPalログイン -> アカウント設定 -> アカウント設定 -> ユーザーの管理）。


---


外部との連携
============
PyCon JPを外部に伝えるために各種サービスを用意します。

.. _event-registration-on-connpass

イベント登録
------------
.. index:: connpass

イベントの参加登録には `connpass <https://connpass.com>`_ を使用しています。
connpass ではイベント公開時に過去の参加者に通知がいくため、2つのグループを使い分けて使用しています。

- `PyCon JP - connpass <http://pyconjp.connpass.com/>`_:
  PyCon JPのイベント参加登録用のグループです。
- `PyCon JPスタッフ - connpass <http://pyconjp-staff.connpass.com/>`_
  PyCon JPのスタッフ活動のイベント用のグループです。スタッフミーティングなどはこちらのグループで作成します。

connpassで有料イベントの開催する場合、PayPalのメールアドレスを設定します。メールアドレスは、イベント種別ごとに別のアドレスを使用します。PyConJP, PyCamp, その他イベントの支払設定を異なるメールアドレスで設定することで、PayPalの履歴でどのイベント向けの入金か見分けるためです（重要）。

* connpassに設定するメールアドレスは、 ``pycon.jpメアド管理`` を参照してください。

* PayPalにメールアドレスを追加する方法については :ref:`paypal` を参照してください。

Blog
----
.. index:: blog, blogger

各種お知らせを記述するためのBlogを用意します。
`PyCon JP Blog <http://pyconjp.blogspot.jp/>`_ は `Blogger <https://www.blogger.com/home>`_ を使用しています。

Blogの運営についての詳細は :ref:`blog` を参照してください。

ソーシャルメディア
------------------
.. index:: twitter, Facebook Pages

PyCon JP ではソーシャルメディアでの告知用に Twitter と Facebook Pages を運用しています。

- Twitterアカウント: `@PyConJ <https://twitter.com/pyconj>`_
- Facebook Pages: `PyCon JP <https://www.facebook.com/pyconjp>`_

BlogとSNSの連携
---------------
.. index:: dlvr.it

Blog で書いた内容を SNS でシェアするために、 `dlvr.it <https://dlvr.it/>`_ というサービスを使用しています。

仕組みとしては、BlogのRSSを定期的に読み込んで、新しい記事が投稿されたら Twitter と Facebook Pages でシェアしています。
