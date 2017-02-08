# apache-php

This docker container installs apache2 and PHP to run PHP applications. 

This container is based on the [official PHP container](https://hub.docker.com/_/php/) but installs PHP from the debian repository. 

This container got intl installed, so it can be used to run cakephp. 

## intalled software

  * apache2
  * php5
  * php5-gd
  * php5-intl
  * php5-mcrypt
  * php5-mysqlnd
  * php5-sqlite
  * php5-tidy


## running the container

```
docker run --rm -p 80:80 -v $(pwd):/var/www/html paulwoelfel/apache-php
```
