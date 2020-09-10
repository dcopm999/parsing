=====
Usage
=====

To use parsing in a project, add it to your `INSTALLED_APPS`:

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
