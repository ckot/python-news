========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-news/badge/?style=flat
    :target: https://readthedocs.org/projects/python-news
    :alt: Documentation Status


.. |travis| image:: https://travis-ci.org/ckot/python-news.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/ckot/python-news

.. |version| image:: https://img.shields.io/pypi/v/python-news.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/python-news

.. |commits-since| image:: https://img.shields.io/github/commits-since/ckot/python-news/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/ckot/python-news/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/python-news.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/python-news

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/python-news.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/python-news

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/python-news.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/python-news


.. end-badges

"news article extractor"

* Free software: BSD 2-Clause License

Installation
============

::

    pip install python-news

Documentation
=============


https://python-news.readthedocs.io/


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
