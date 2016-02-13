================
 テンプレート集
================

PyCon JP の運営で使用しているファイルのテンプレートを下記フォルダで公開しています。コピーしてご自由にお使いください。

- https://drive.google.com/drive/u/0/folders/0B_bw8GEmTD5OOElXMC0ydWhuTVE

サービス管理
============
:URL: https://drive.google.com/open?id=16QYbDAcl6Zvtrckhyag06u3w-UpITSoOZQD4VLbm2Bs

各種サービスのユーザー名、パスワードを管理するためのシートです。

スタッフにお知らせシート
========================
:URL: https://drive.google.com/open?id=12guOzi8q6iV2f33eFmyggnNb3SWDIPgOkYXZNZDt2HQ

指定した日時に任意のメッセージをSlackのchannelに送信するシートです。

Webhook URLの作成
-----------------
Slack と連携するための Incoming Webhook URL を生成します。

Slack の `Incoming WebHooks <https://slack.com/apps/A0F7XDUAZ-incoming-webhooks>`_ のページを開き、任意のチームの Incoming Webhook を生成します。

生成した **Webhook URL** をスクリプトの ``webhookurl`` に設定します。

トリガー設定
------------

使用する場合は定期実行するためのトリガーを設定する必要があります。
トリガーの設定手順は以下のとおりです。

1. ツール→スクリプトエディタ...
2. リソース→現在のプロジェクトのトリガー
3. 「トリガーが設定されていません。今すぐ追加するにはここをクリックしてください。」をクリック
4. 「notifyToMembers/時間主導型/時タイマー/1時間ごと」を指定して **保存** をクリック

スタッフ名簿
============
:URL: https://drive.google.com/open?id=1UtjiFVgR6GAr0cTK2x8FwK5j7Icz2z_LeT3HQXs0DIs
:URL: https://drive.google.com/open?id=1Yl_tRluqop3x_7mu9MNMTLGojJXP2sy7JCGBxf1ROys

スタッフの連絡先を記入してもらうシートと、スタッフ応募用のフォームです。


Twitter/Facebook通知シート
==========================
:URL: https://drive.google.com/open?id=1m9GXQX7qVvDSqY7mjMIHtLSIAUTyhN3D05KI5qttwvw

指定した日時に任意のメッセージをTwitter/Facebookに送信するシートです。

Twitter/Facebook それぞれと連携するために以下の準備が必要です。

Facebook連携
------------
`Graph API Explorer <https://developers.facebook.com/tools/explorer>`_ を表示し、通知を送信する先になる Facebook Pages への **Access Token** を取得します。

取得した Access Token をスクリプトの ``access_token`` に指定します。

Twitter連携
-----------
Twitter連携をするためには、あらかじめOAuth認証を完了させる必要があります。

下記ページの内容を参考に、以下を実施します。

1. `Twitter Application Management <https://apps.twitter.com/>`_ で Twitter アプリを作成
2. Twitterアプリ側の設定で Callback URL を記述
3. OAuth認証を実施

`Google Apps ScriptでOAuthConfigのサポートが終了してTwitter botが危険そうだったので変更 - きじとら <https://kijtra.com/article/twitter-api-for-google-apps-script-without-oauthconfig/>`_

トリガー設定
------------
使用する場合は定期実行するためのトリガーを設定する必要があります。
トリガーの設定手順は以下のとおりです。

1. ツール→スクリプトエディタ...
2. リソース→現在のプロジェクトのトリガー
3. 「トリガーが設定されていません。今すぐ追加するにはここをクリックしてください。」をクリック
4. 「snsbot/時間主導型/分タイマー/10分ごと」を指定して **保存** をクリック

