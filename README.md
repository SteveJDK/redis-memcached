# redis-memcached

## Latest version:
- ENV MEMCACHED_VERSION 1.4.33 
- ENV REDIS_VERSION 2.8.19



## How to use this image

```shell
$ docker run --restart=always -d --name redismem -p 11211:11211 -p 6379:6379 xnowr/redis-memcached
```
