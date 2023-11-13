# WordPress in Docker

It'll help to quickly deploy wordpress via docker.


## How it works

You should have a database - you can use my [docker-maraidb](https://github.com/iSmartyPRO/docker-mariadb) repository

#### Commands

```
cp .env.sample .env
vim .env
```

edit config files using your data, such as container name, database configuration, ports etc.


Launch docker container
```
docker-compose up -d
```
