# mysite
Django test project

1. How to use:

In mysql (root, without password)
    CREATE DATABASE testdjango;

(opt.) python manage.py sqlmigrate polls 0001
Will give what SQL that migration would run.

python manage.py migrate


2. How to test

python manage.py test polls

Please refer to https://docs.djangoproject.com/en/1.8/intro/tutorial01/
