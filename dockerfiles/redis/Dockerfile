FROM redis
RUN cd /usr/local/etc
ADD redis.conf /usr/local/etc
CMD ["redis-server", "/usr/local/etc/redis.conf"]