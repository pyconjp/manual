=======================
 reStructuredText 入門
=======================

このドキュメントは基本的に reStructuredText で書いてるので、最低限抑えておくとよい書き方について説明します。詳しい使い方は下の方にある参考資料を見てください。

段落
====
空行をあけると段落になります。

.. list-table::
   :header-rows: 1
   :widths: 50 50

   * - 入力例
     - 出力例
   * - ::

         空行をあけると

         別の段落になって、
         改行だけだと一つの段落にまとまります。
     - 空行をあけると

       別の段落になって、
       改行だけだと一つの段落にまとまります。

リスト
======
数字なしの箇条書きと、数字ありの列挙リスト

.. list-table::
   :header-rows: 1
   :widths: 50 50

   * - 入力例
     - 出力例
   * - ::

         * 箇条書き
         * です

           * ネストするときは空行が必要

     -
       * 箇条書き
       * です

         * ネストするときは空行が必要

   * - ::

         1. 数字付きの
         2. 列挙リストです

            1. ネストするときはやっぱり空行が必要

     -
         1. 数字付きの
         2. 列挙リストです

            1. ネストするときはやっぱり空行が必要

インラインマークアップ
======================
.. list-table::
   :header-rows: 1
   :widths: 50 50

   * - 入力例
     - 出力例
   * - ::

          文章中に **太字** で表示
     - 

       文章中に **太字** で表示
   * - ::

          文章中に ``固定幅フォント(Monospaced Font)`` で表示
     - 

       文章中に ``固定幅フォント(Monospaced Font)`` で表示

リンク
======
.. list-table::
   :header-rows: 1
   :widths: 50 50

   * - 入力例
     - 出力例
   * - ::

          http://manual.pycon.jp/
     - 

       http://manual.pycon.jp/
   * - ::

          `PyCon JP 運営マニュアル <http://manual.pycon.jp/>`_
     - 

       `PyCon JP 運営マニュアル <http://manual.pycon.jp/>`_

         
参考資料
========
* `はやわかり reStructuredText <http://www.planewave.org/translations/rst/quickref.html/restructuredtext.html>`_
* `reStructuredText入門 — Sphinx 1.4.4 ドキュメント <http://docs.sphinx-users.jp/rest.html>`_
* `Sphinxマークアップ集 — Sphinx 1.4.4 ドキュメント <http://docs.sphinx-users.jp/markup/index.html>`_
* `O'Reilly Japan - Sphinxをはじめよう <https://www.oreilly.co.jp/books/9784873116488/>`_

