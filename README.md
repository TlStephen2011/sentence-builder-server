# server

Ensure Nodejs > 14 is installed and port 3000 is free to use

## Project setup

Ensure Mysql docker container is running

```
docker run -dit -p 3306:3306 --name mysql -e MYSQL_ROOT_PASSWORD=password mysql
```

Once running create database SentenceBuilder

```
npm install
```

### Compiles and hot-reloads for development
```
npm run start
```

###


