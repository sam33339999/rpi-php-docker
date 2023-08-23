FROM docker.io/phpswoole/swoole:5.0.3-php8.2

RUN docker-php-ext-install bcmath && \
    apt update && \
    apt install -y vim wget nodejs npm procps && \
    npm install -g yarn && \
    rm -rf /var/lib/apt/lists/*

EXPOSE 8080

WORKDIR /data

VOLUME [ "/data" ]