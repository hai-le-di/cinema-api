# Cinema API

API service for cinema management written on DRF

## Installing using GitHub

Install PostgresSQL and create db

```
git clone https://github.com/hai-le-di/cinema-api.git
cd cinema_api
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
set POSTGRES_HOST=<your db hostname>
set POSTGRES_DB=<your db name>
set POSTGRES_USER=<your db username>
set POSTGRES_PASSWORD=<your db user password>
set SECRET_KEY=<your secret key>
python manage.py migrate
python manage.py runserver
```

## Run with docker

```
Docker should be installed
docker-compose build docker-compose up
```

## Getting access

* create user via /api/user/register/
* get access token via /api/user/token/


## Features

* JWT authenticated
* Admin panel /admin/
* Documentation is located at /api/doc/swagger/
* Managing orders and tickets
* Creating movies with genres, actors
* Creating cinema halls
* Adding movie sessions
* Filtering movies and movie sessions

