****************************
Mopidy-BeetsLocal
****************************

.. image:: https://img.shields.io/pypi/v/Mopidy-BeetsLocal.svg?style=flat
    :target: https://pypi.python.org/pypi/Mopidy-BeetsLocal/
    :alt: Latest PyPI version

.. image:: https://img.shields.io/pypi/dm/Mopidy-BeetsLocal.svg?style=flat
    :target: https://pypi.python.org/pypi/Mopidy-BeetsLocal/
    :alt: Number of PyPI downloads

.. image:: https://img.shields.io/travis/rawdlite/mopidy-beets-local/master.png?style=flat
    :target: https://travis-ci.org/rawdlite/mopidy-beets-local
    :alt: Travis CI build status

.. image:: https://img.shields.io/coveralls/rawdlite/mopidy-beets-local/master.svg?style=flat
   :target: https://coveralls.io/r/rawdlite/mopidy-beets-local?branch=master
   :alt: Test coverage

Access a local beets library via beets native api.
No running beets web process is required.
Search by specific fields is fully supported.


Installation
============

Install by running::

    pip install Mopidy-BeetsLocal



Configuration
=============

Before starting Mopidy, you must add configuration for
Mopidy-BeetsLocal to your Mopidy configuration file::

    [beetslocal]
    enabled = true
    beetslibrary = /<your path>/beetslibrary.blb
    use_original_release_date = false

Project resources
=================

- `Source code <https://github.com/rawdlite/mopidy-beets-local>`_
- `Issue tracker <https://github.com/rawdlite/mopidy-beets-local/issues>`_
- `Development branch tarball <https://github.com/rawdlite/mopidy-beets-local/archive/master.tar.gz#egg=Mopidy-BeetsLocal-dev>`_


Changelog
=========
v.0.0.7
---------------------------------------
-Media Library in ncmpcpp works now.
-Various Artist limited to genre

v0.0.6
---------------------------------------
added browsing

v0.0.5
----------------------------------------
added albums in lookup and search
fixed links in Project resources

v0.0.4
----------------------------------------
cleanup

v0.0.3 (UNRELEASED)
----------------------------------------
Switched to URI schema 'beetslocal'

v0.0.2 (UNRELEASED)
----------------------------------------

Introducing new optional config option 'use_original_release_date'.
Path decoding now hopefully working for different locale.
Tracks have release date and disc_num.

v0.0.1 (UNRELEASED)
----------------------------------------

- Initial release.
