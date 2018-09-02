# Shenron

### A minimal version of hosting dockerize containers for PHP based projects.

#### Based on caddy and php-fpm container.

1. Clone the repository
2. copy .env-example as .env file
3. run `docker-compose up -d`
4. Add a new config in `docker/caddy/sites` folder to host a new project. Then rebuild docker caddy docker container by `docker-compose up --build caddy`