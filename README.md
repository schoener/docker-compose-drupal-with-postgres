# Simple Docker Compose tutorial to setup Drupal with Postgres DB

* will be started with `docker-compose up -d`
* after the drupal and postgres container are up navigate to `localhost:8080` and install drupal on your machine. All required fields of Postgres has a default value which is **postgres**. The host for Postgres is **postgres** aswell. 
* to stop docker-compose call `docker-compose down -v` (`-v` is for remove volumes aswell)