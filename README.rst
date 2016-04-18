========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |coveralls|
        | |landscape| |codacy| |codeclimate|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/structured_prediction/badge/?style=flat
    :target: https://readthedocs.org/projects/structured_prediction
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/redwardstern/structured_prediction.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/redwardstern/structured_prediction

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/redwardstern/structured_prediction?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/redwardstern/structured_prediction

.. |requires| image:: https://requires.io/github/redwardstern/structured_prediction/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/redwardstern/structured_prediction/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/redwardstern/structured_prediction/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/redwardstern/structured_prediction

.. |landscape| image:: https://landscape.io/github/redwardstern/structured_prediction/master/landscape.svg?style=flat
    :target: https://landscape.io/github/redwardstern/structured_prediction/master
    :alt: Code Quality Status

.. |codacy| image:: https://img.shields.io/codacy/REPLACE_WITH_PROJECT_ID.svg?style=flat
    :target: https://www.codacy.com/app/redwardstern/structured_prediction
    :alt: Codacy Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/redwardstern/structured_prediction/badges/gpa.svg
   :target: https://codeclimate.com/github/redwardstern/structured_prediction
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/structured-prediction.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/structured-prediction

.. |downloads| image:: https://img.shields.io/pypi/dm/structured-prediction.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/structured-prediction

.. |wheel| image:: https://img.shields.io/pypi/wheel/structured-prediction.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/structured-prediction

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/structured-prediction.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/structured-prediction

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/structured-prediction.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/structured-prediction


.. end-badges

Survey of structured prediction and probabilistic graphical models

* Free software: BSD license

Installation
============

::

    pip install structured-prediction

Documentation
=============

https://structured_prediction.readthedocs.org/

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
