=============================
parsing
=============================

.. image:: https://badge.fury.io/py/parsing.svg
    :target: https://badge.fury.io/py/parsing

.. image:: https://travis-ci.org/dcopm999/parsing.svg?branch=master
    :target: https://travis-ci.org/dcopm999/parsing

.. image:: https://codecov.io/gh/dcopm999/parsing/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/dcopm999/parsing

Your project description goes here

Documentation
-------------

The full documentation is at https://parsing.readthedocs.io.

Quickstart
----------

Install parsing::

    pip install parsing

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'parsing.apps.ParsingConfig',
        ...
    )

Add parsing's URL patterns:

.. code-block:: python

    from parsing import urls as parsing_urls


    urlpatterns = [
        ...
        url(r'^', include(parsing_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox


Development commands
---------------------

::

    pip install -r requirements_dev.txt
    invoke -l


Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
