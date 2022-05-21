:orphan:

**************
0.8.3.4 -> 0.9
**************

.. _ajouts_100:

Added
=====

* Use of YAML files instead of XML for exports configuration
* New preference to show/hide borders around PDF member cards (`#184 <https://bugs.galette.eu/issues/184>`_)

.. _bogues_100:

Fixed
=====

* Update issues (not defined constants) (`#1615 <https://bugs.galette.eu/issues/1615>`_)
* Fatal error when cookie not set after login (`#1617 <https://bugs.galette.eu/issues/1617>`_)
* Sort members by status  (`#1618 <https://bugs.galette.eu/issues/1618>`_)
* Several PHP 8.1 compatibility fixes (`#1626 <https://bugs.galette.eu/issues/1629>`_)

.. _souscapot_100:

Under the hood...
=================

* Template rendering is now assumed by `Twig <https://twig.symfony.com/>`_ instead of `Smarty <https://smarty.net/>`_
* Use of `Fomantic UI <https://fomantic-ui.com/>`_ framework for whole display
* Update third party libraries
