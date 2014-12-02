dockerfile-redis
================

    docker pull pihizi/redis
    docker run --name debade-redis \
        --dns 127.17.42.1 \
        -v /dev/log:/dev/log \
        -p 6379:6379 \
        -d pihizi/redis
