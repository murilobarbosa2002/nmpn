# NMPN

#### Disclaimer: I apologize for the poor English, and possible spelling errors, I hope I have helped with something!

### (N)GINX
Default nginx settings are found in the path ./nginx/default.conf,If it is a laravel application, just add  public path to root in default.conf
<br>
example: <code> root /var/www/project/public </code>
### (M)YSQL
The version used in this environment is version 8, if you need another just change it to the desired one in docker-compose.yml
<br>
example: <code> image: mysql:5.7 </code>
### (P)HP
The version used in this environment is version 8.1-FPM because I'm using NGINX , if you need another just change it to the desired one in ./php/Dockerfile
<br>
example: <code> FROM php:7.4-fpm </code>
### (N)ODE
The version used in this environment is version LTS, if you need another just change it to the desired one in docker-compose.yml
<br>
example: <code> image: node:latest </code>

#### PHP My Admin
PHP My Admin is just a bonus, because I like it to work with, if you want to change or remove it from the environment, just remove it or change it in docker-compose.yml

#### Links

For more information, or possible modifications, follow the Docker Hub links below:
<br>
[NGINX](https://hub.docker.com/_/nginx)
<br>
[MYSQL](https://hub.docker.com/_/mysql)
<br>
[PHP](https://hub.docker.com/_/php)
<br>
[NODE](https://hub.docker.com/_/node)
<br>
[PHPMYADMIN](https://hub.docker.com/_/phpmyadmin)