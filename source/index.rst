.. Galette documentation master file, created by
   sphinx-quickstart on Wed Jun 22 13:49:01 2011.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Galette's documentation
=======================

`Galette <https://galette.eu>`_ is a `Free/Libre Open Source <https://en.wikipedia.org/wiki/Free_and_open-source_software>`__ membership management web application dedicated towards non profit organizations.

.. rst-class:: docs install_doc

:doc:`installation manual <installation/index>`

.. rst-class:: docs user_doc

:doc:`user manual <usermanual/index>`

.. rst-class:: docs plugins_doc

:doc:`plugins documentation <plugins/index>`

.. toctree::
   :maxdepth: 2

   installation/index.rst
   usermanual/index.rst
   faq/index.rst
   plugins/index.rst

.. toctree::
   :maxdepth: 1

   command-line.rst
   source_code.rst
   changelog.rst

*************
About Galette
*************

* `Galette website <https://galette.eu>`_,
* :doc:`a GIT repository to manage Galette source code <source_code>`,
* mailing lists,
* ...

There are also a few external services:

* `a bug tracker <https://bugs.galette.eu/projects/galette/>`_, to declare issues or to ask for evolutions,
* `a wonderfull :p documentation <https://doc.galette.eu>`_, you are currently reading,
* `a voting system <https://vote.galette.eu>`_, you can vote for features,
* `a Telemetry application <https://telemetry.galette.eu>`_ which handles and displays Telemetry data received from volunteer Galette instances.

Galette documentation is released under the terms of the `Attribution-ShareAlike 3.0 Unported  <https://creativecommons.org/licenses/by-sa/3.0/>`_ license, written using `reStructuredText <http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html>`_ and built with `Sphinx documentation builder <https://www.sphinx-doc.org>`_.

Sphinx allows to build documentation in various formats from the same sources. Galette's documentation is therefore available as HTML, PDF and EPUB formats; thanks to `Read the docs <https://readthedocs.io>`_.
