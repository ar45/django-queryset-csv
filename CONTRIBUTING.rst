contributing
------------

in order for a pull request to be merged, please make sure it meets the following criteria:

1. all unit tests pass for all supported versions of python and django.
2. every newly added line of code is exercised by at least one unit tests.
3. all code is compliant with PEP8 style conventions.


development setup
-----------------
to setup a development environment, run the following commands::

  ~/django-queryset-csv/$ pip install -r dev_requirements.txt
  ~/django-queryset-csv/$ python setup.py install


unit testing
------------

to run the unit tests, run the following commands::

  ~/django-queryset-csv/$ cd test_app
  ~/django-queryset-csv/test_app/$ python manage.py test


demo testing
------------

to ensure the app behaves as expected, run the following::

  ~/django-queryset-csv/$ cd test_app
  ~/django-queryset-csv/test_app/$ python manage.py runserver

then, visit ``http://localhost:8000/`` in your browser and confirm it produces a valid CSV.


  
