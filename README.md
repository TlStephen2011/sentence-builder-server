# server

Ensure Nodejs > 14 is installed and port 3000 is free to use

## Project setup

Ensure Mysql docker container is running

```
docker run -dit -p 3306:3306 --name mysql -e MYSQL_ROOT_PASSWORD=password mysql
```

Once running create database SentenceBuilder


### Install packages

```
npm install
```

### Compiles and hot-reloads for development
```
npm run start
```

###

### First run

Database tables will be created on first run with relevant data. For the second run please comment out table population in app.js
