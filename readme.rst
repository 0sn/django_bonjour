django-bonjour
==============

This is a dinky little module that you can drop into your django app to add a command "bonjour".

::

    python manage.py bonjour

How it works
------------

I swiped the runserver code from django-admin and the bonjour code from Turbogears. It registers the server at "Django: " + the name of the settings module.

Note that the server now runs at http://0.0.0.0:8000 and that can't be changed. I'm lazy. It also only works with dns-sd which as far as I know only exists on Leopard.
