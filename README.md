# mysite
Django test project

1. How to use:

1.1 Create Database
In mysql (root, without password)
    CREATE DATABASE testdjango;

(opt.) python manage.py sqlmigrate polls 0001
Will give what SQL that migration would run.

1.2 Create tables
python manage.py migrate

1.3 Start up server
python manage.py runserver 0:8000

1.4 Access
For user
http://127.0.0.1:8000/polls/
For admin
http://10.43.114.43:8000/admin/
For shell access
python manage.py shell

2. How to test

python manage.py test polls

Please refer to https://docs.djangoproject.com/en/1.8/intro/tutorial01/
