============================
 PyCon JP organizers manual
============================

|docs|

.. |docs| image:: https://readthedocs.org/projects/pycon-jp-manual/badge/?version=latest
    :alt: Documentation Status
    :scale: 100%
    :target: http://manual.pycon.jp/?badge=latest

How to build
============

.. code-block:: sh

   $ git clone https://github.com/pyconjp/manual.git
   $ cd manual
   $ virtualenv env
   $ . env/bin/activate
   (env)$ pip install -r requirements.txt
   (env)$ make html
   (env)$ open build/html/index.html

Theme
=====
- `vimalkvn/solar-theme: Theme for Python Sphinx <https://github.com/vimalkvn/solar-theme>`_

How to contribute
=================
- このマニュアルをcloneしてガンガン commit したり Pull Request ください
- PyCon JP スタッフはこのリポジトリへの書き込み権限があるので、直接 commit/push してもらって構いません
- スタッフじゃない人も Pull Request もらえたら喜んで merge するので、typo 指摘とかなんでももらえると嬉しいです

Reference
=========
- `PyCon JP Blog: 「PyCon JP 運営マニュアル」を執筆中 <http://pyconjp.blogspot.jp/2016/03/pyconjp-manual.html>`_

