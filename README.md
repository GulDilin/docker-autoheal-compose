# docker-autoheal-compose
Docker compose file for docker autorestart unhealthy containers

### How to use
- Start with `docker-compose up -d`
- Add label `autoheal=true` to service container, which you want to enable autorestart if unhealthy
