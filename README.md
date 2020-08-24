# Dummy_django-login_logut-page-with-error-logging-

create a new auth directory for our code on the Desktop
install Django with Pipenv
start the virtual environment shell
create a new Django project called config
create a new Sqlite database with migrate
run the local server
Here are the commands to run:

$ pipenv install django

$ pipenv shell
(accounts) $ django-admin.py startproject config .

(accounts) $ python manage.py migrate

(accounts) $ python manage.py runserver

# To create a new user 
- run the command python manage.py createsuperuser

- (accounts) $ python manage.py createsuperuser

Username (leave blank to use your system name):

Email address: abc@gmail.com

Password:

Password (again):

Superuser created successfully.
# Link to the page (will run on local host)
http://127.0.0.1:8000/admin/
