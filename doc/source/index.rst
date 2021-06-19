.. ID documentation master file, created by
   sphinx-quickstart on Sat Dec 18 08:18:09 2017.

Sphinx Documentation Template
=============================

A sphinx documentation template using a modified version of the sphinx-bootstrap_ theme and including support for diagrams using plantweb_.

.. uml::

   skinparam monochrome true
   skinparam handwritten true

   actor You
   "sphinx-doc-template" --> You: copy
   You --> You: customize
   You --> GitHub: push
   GitHub --> RTD: WebHook
   RTD --> RTD: build
   You <-- RTD: Read The Docs


.. toctree::
   :maxdepth: 2
   :caption: Contents:

   setup
   diagrams
   markdown


Indices and tables
==================

* :ref:`genindex`
* :ref:`search`


.. _sphinx-bootstrap: https://ryan-roemer.github.io/sphinx-bootstrap-theme/
.. _plantweb: https://plantweb.readthedocs.io/index.html