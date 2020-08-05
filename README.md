# Laradocker 
Simple Laravel project with docker files including nginx, redis, mysql and php-fpm

#### Especifications
<table>
<tr><td>Nginx</td><td>1.15.0</td></tr>
<tr><td>PHP-FPM</td><td>7.4.8</td></tr>
<tr><td>Mysql</td><td>5.7.31</td></tr>
<tr><td>Redis</td><td>6.0.5</td></tr>
</table>

### Getting started
Just clone the project and run the following command:
```
docker-compose up -d
```
_make sure that some ports are free to use (db 3306, app 8000)._

access the app on localhost:8000
- [app](http://localhost:8000)

##### Dockerhub
- [Docker hub laravel from scratch](https://hub.docker.com/r/tiagofs/laravel-optmized)
- [Docker hub - golang from sccratch](https://hub.docker.com/r/tiagofs/codeeducation)

Thanks!
