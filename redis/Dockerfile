FROM openestuary/centos

ENV  REDIS_VERSION redis-3.24
ENV  PATH /usr/local/bin:/usr/local/redis/bin:$PATH

ADD  redis /usr/local/redis
RUN  mkdir -p /usr/local/redis/db

EXPOSE 6379
CMD ["/usr/local/redis/bin/redis-server", "/usr/local/redis/config/redis.conf"]
