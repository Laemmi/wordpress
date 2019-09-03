# Wordpress with composer

## Start
`docker-compose up -d`

`docker exec -it wordpress_php_1 /bin/bash`

Install composer (https://getcomposer.org/download/)

`php composer.phar install`

http://localhost:8080/

Enjoy wordpress ;-)

## Usage

Apache logfiles: .docker/apache/log

Mysql Data: .docker/mysql/data
