.. This README is meant for consumption by humans and pypi. Pypi can render rst files so please do not use Sphinx features.
   If you want to learn more about writing documentation, please check out: http://docs.plone.org/about/documentation_styleguide.html
   This text does not appear on pypi or github. It is a comment.

.. image:: https://github.com/collective/ploneconf.site/actions/workflows/plone-package.yml/badge.svg
    :target: https://github.com/collective/ploneconf.site/actions/workflows/plone-package.yml

.. image:: https://coveralls.io/repos/github/collective/ploneconf.site/badge.svg?branch=main
    :target: https://coveralls.io/github/collective/ploneconf.site?branch=main
    :alt: Coveralls

.. image:: https://codecov.io/gh/collective/ploneconf.site/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/collective/ploneconf.site

.. image:: https://img.shields.io/pypi/v/ploneconf.site.svg
    :target: https://pypi.python.org/pypi/ploneconf.site/
    :alt: Latest Version

.. image:: https://img.shields.io/pypi/status/ploneconf.site.svg
    :target: https://pypi.python.org/pypi/ploneconf.site
    :alt: Egg Status

.. image:: https://img.shields.io/pypi/pyversions/ploneconf.site.svg?style=plastic   :alt: Supported - Python Versions

.. image:: https://img.shields.io/pypi/l/ploneconf.site.svg
    :target: https://pypi.python.org/pypi/ploneconf.site/
    :alt: License



Backend for plone6 training (https://training.plone.org/5/mastering-plone/index.html) Includes all chapters up to 49. exclude 38,39.
==========

The chapters 50-52 are implemented on the branch "chapter_50", cheackout guide:
==========

Steps:
--------
- after plone projects buildout cd to src/ploneconf.site directory
- git fetch origin chapter_50 && git checkout chapter_50
- return to project root and run the instance

==============
ploneconf.site
==============

plone conference on mars

Features
--------

- Can be bullet points


Examples
--------

This add-on can be seen in action at the following sites:
- Is there a page on the internet where everybody can see the features?


Documentation
-------------

Full documentation for end users can be found in the "docs" folder, and is also available online at http://docs.plone.org/foo/bar


Translations
------------

This product has been translated into

- Klingon (thanks, K'Plai)


Installation
------------

Install ploneconf.site by adding it to your buildout::

    [buildout]

    ...

    eggs =
        ploneconf.site


and then running ``bin/buildout``


Authors
-------

Provided by awesome people ;)


Contributors
------------

Put your name here, you deserve it!

- ?


Contribute
----------

- Issue Tracker: https://github.com/collective/ploneconf.site/issues
- Source Code: https://github.com/collective/ploneconf.site
- Documentation: https://docs.plone.org/foo/bar


Support
-------

If you are having issues, please let us know.
We have a mailing list located at: project@example.com


License
-------

The project is licensed under the GPLv2.
