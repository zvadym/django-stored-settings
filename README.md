Django DbSettings
---------------------

about...


Installation
============

pip install git+git://github.com/zvadim/django-db-settings.git

Add `db_settings` to your `INSTALLED_APPS`.

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'db_settings',
    )


Add new content processor

.. code-block:: python

    TEMPLATE_CONTEXT_PROCESSORS = (
        ...
        db_settings.context_processors.settings
    )


Use
============
in template 
    
    {{ db_settings.my_key }}