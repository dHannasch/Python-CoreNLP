========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor|
        |
    * - package
      - | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-corenlp/badge/?style=flat
    :target: https://readthedocs.org/projects/python-corenlp
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/dHannasch/python-corenlp.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/dHannasch/python-corenlp

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/dHannasch/python-corenlp?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/dHannasch/python-corenlp

.. |commits-since| image:: https://img.shields.io/github/commits-since/dHannasch/python-corenlp/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/dHannasch/python-corenlp/compare/v0.0.0...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

Installation
============

::

    pip install corenlp

You can also install the in-development version with::

    pip install https://github.com/dHannasch/python-corenlp/archive/master.zip


Documentation
=============


https://python-corenlp.readthedocs.io/


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
