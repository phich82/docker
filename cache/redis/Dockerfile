FROM redis

RUN apt-get -y update && apt-get -y install vim
RUN apt-get -y install procps

COPY conf/redis.conf /usr/local/etc/redis/redis.conf

CMD [ "redis-server", "/usr/local/etc/redis/redis.conf" ]
