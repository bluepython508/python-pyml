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
        | |coveralls|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-pyml/badge/?style=flat
    :target: https://readthedocs.org/projects/python-pyml
    :alt: Documentation Status


.. |travis| image:: https://travis-ci.org/bluepython508/python-pyml.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/bluepython508/python-pyml

.. |coveralls| image:: https://coveralls.io/repos/bluepython508/python-pyml/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/bluepython508/python-pyml

.. |version| image:: https://img.shields.io/pypi/v/pyml.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/pyml

.. |commits-since| image:: https://img.shields.io/github/commits-since/bluepython508/python-pyml/v0.0.1.svg
    :alt: Commits since latest release
    :target: https://github.com/bluepython508/python-pyml/compare/v0.0.1...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/pyml.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/pyml

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pyml.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/pyml

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pyml.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/pyml


.. end-badges

A basic internal XML-generating DSL in Python 3.

* Free software: MIT license

Installation
============

::

    pip install pyml

Documentation
=============


https://python-pyml.readthedocs.io/


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
