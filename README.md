
# Cinema API

Django project for managing movies and tickets in cinema

## Installing / Getting started

Docker must be already installed on your computer.

```shell
git clone https://github.com/lenasharabura/cinema-api.git
cd cinema-api/
docker-compose up    
```

The server will start, and you will be able to use the application.
create user on /api/user/register/
get access token on /api/user/token/

## Features

Documentation is located at /api/doc/swagger/
* Managing actors, genres
* Creating movies with genres, actors
* Creating cinema halls
* Managing orders and tickets
* Creating movie sessions with associated cinema hall
* Filtering movies and movie sessions
* User and superuser functionality
* Admin panel for advanced managing
