============================
 PyCon JP organizers manual
============================

|docs|

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

.. |docs| image:: https://readthedocs.org/projects/pycon-jp-manual/badge/?version=latest
    :alt: Documentation Status
    :scale: 100%
    :target: http://manual.pycon.jp/?badge=latest
