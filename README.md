# Cinema API

API service for cinema management written on DRF

## Installing using GitHub

Install PostgresSQL and create db

* git clone 
* cd cinema_API
* python -m venv venv
* source venv/bin/activate
* pip install -r requirements.txt
* set DB_HOST=<your db hostname>
* set DB_NAME=<your db name>
* set DB_USER=<your db username>
* set DB_PASSWORD=<your db user password>
* set SECRET_KEY=<your secret key>
* python manage.py migrate
* python manage.py runserver