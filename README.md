# docker-mysql-apache-pma

Docker Compose for local development with Apache 7.1.2, MySQL 5.5, PhpMyAdmin.

## MySQL

Put `*.sql` files in `mysql` folder.

## Apache

All website files go to the `www` folder.

## Run

`docker-composer up -d`

This will run a dev environment:

- localhost:8001: Apache/Website
- localhost:8002: PhpMyAdmin
- locahost:8003: MySQL

## Stop

`docker-compose down`

## Remove

`docker-compose rm -v`
