# Django HumansTXT

Django HumansTXT will make it easy to you to serve humans.txt file.

## Quickstart

Install django-humanstxt using pip (we do recommend to do it in a virtualenv).

.. code-block:: sh

    pip install django-humanstxt

To integrate it into a Django project, simply add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = [
        # some interesting stuff...
        'humanstxt',
        # some other stuff...
    ]

.. code-block:: python

    urlpatterns = [
        # ...
        url(r'^humans\.txt', include('humanstxt.urls')),
        # ...
    ]

.. code-block:: sh

    python manage.py migrate


You're now ready to use the app.
