## Description
Apps Logistic Services

## Requirtment / Tech Stack
While this project was being created, the technology stack was used is following :

- [x] Node Version 18 or lts/hydrogen
- [x] Nestjs version 9
- [x] Typeorm version 10
- [x] Postgres version 16.2
- [x] Nest Swager version 7.3.1 
- [x] Docker
- [x] Docker Compose version

## Installation
Each inside the project nestjs you should install dependency before.

 
```bash
From root project :
$ cd ./be-apps-auth
$ nvm use
$ npm install

From root project :
$ cd ./be-apps-logistic
$ nvm use
$ npm install
```

## Environtment
On each project nestjs please create .env file and assign the value as you need with structure : 

```
# APP
PORT=****

# DATABASE
PG_PORT=****
PG_HOST==****
PG_USER==****
PG_PASS==****
PG_DB==****

# JWT
JWT_SECRET=***
```
Or you can find on file .env.example for each project inside.

## Running the app
From Root Project: 
```
$ docker compose up
```


## Running test