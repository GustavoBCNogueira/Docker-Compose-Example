# Docker-Compose-Example
Simple docker compose example containing MariaDB, NextCloud, Redis and Plex as services

run with `docker-compose up -d` 

if you want to monitor NextCloud's traffic on Redis, run `docker inspect name_of_the_redis_container`, get the container's IP address and run `redis-cli -a password_set_in_docker_compose -h IP_address monitor`.
