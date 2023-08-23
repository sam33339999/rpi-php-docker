FROM docker.io/phpswoole/swoole:4.8-php7.4-alpine

RUN docker-php-ext-install bcmath

EXPOSE 8080

WORKDIR /data

VOLUME [ "/data" ]