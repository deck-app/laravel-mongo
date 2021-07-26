# laravel + MongoDB
## Introduction
Laravel is a web application framework for PHP, released as free and open-source software under the MIT License.

The Bitnami Laravel Development Container has been carefully engineered to provide you and your team with a highly reproducible Laravel development environment. We hope you find the Bitnami Laravel Development Container useful in your quest for world domination. Happy hacking!

## Getting started
The quickest way to get started with the Bitnami Laravel Development Container is using docker-compose.

Begin by creating a directory for your Laravel application:
```
mkdir ~/myapp
cd ~/myapp
```
Clone the application directory:
```
$ git clone https://github.com/deck-app/laravel.git
$ cd laravel
```
Finally launch the Laravel application development environment using:
```
$ docker-compose up -d
```
DataBase Configuration 
```
open <localpath>.env file 
```
Edit the line 
```
DB_CONNECTION=mongo
DB_HOST=mongo
DB_PORT=27017
DB_DATABASE=<Create DB>
DB_USERNAME=root
DB_PASSWORD=
```
