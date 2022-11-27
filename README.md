# PhoneGarage (E-Commerce site) with Django Framework

## How to setup and run the Project

* Set up a virtual environment and install django and the libraries used in this project from the requirements.txt file using:~
`pip install -r requirements.txt`

* Remember to run:~ `python manage.py collectstatic` 
command to collect static files into STATIC_ROOT

* To run the application enter command :~ `python manage.py runserver`

* To create a fresh database remove the database file and the migrations and run commands:~

* Delete the sqlite database file (often db.sqlite3) in your django project folder (or wherever you placed it)
* Delete everything except __init__.py file from migration folder in all django apps (eg: rm */migrations/0*.py)
* Make changes in your models (models.py).
* Run below commands:
`python manage.py makemigrations`
`python manage.py migrate`

* Create admin user
`python manage.py createsuperuser`
