Installation
============

#. Run ``pip install coderedcms``
#. Run ``coderedcms start mysite``
#. Enter the mysite project with ``cd mysite/``.
#. Run ``python manage.py migrate`` to create the core models.
#. Run ``python manage.py createsuperuser`` to create the initial admin user.
#. Run ``python manage.py runserver`` to launch the development server, and go to
   http://localhost:8000 in your browser, or http://localhost:8000/admin/ to log in
   with your admin account.

You now have CodeRed CMS up and running. Next, :doc:`customize_design`
