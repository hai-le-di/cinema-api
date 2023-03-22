# Cinema API

API service for cinema management written on DRF

## Installing using GitHub

Install PostgresSQL and create db

```
git clone https://github.com/hai-le-di/cinema-api.git
cd cinema_api
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
create .env file with environment variables listed in .env_sample
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

## Test creds and token
```
email="testuser@example.com", 
password="testpassword"
```

