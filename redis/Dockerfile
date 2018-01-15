FROM hub.c.163.com/library/redis 

MAINTAINER icoolyy icoolyy@163.com

COPY 6379.conf /usr/local/etc/redis/redis.conf

RUN mkdir -p /data/test/redis-log/

CMD [ "redis-server", "/usr/local/etc/redis/redis.conf" ]
