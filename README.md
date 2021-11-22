# Easy Local Database

Easy to install zero-configuration local database.


## Installation

1. [Install Docker](https://docs.docker.com/get-docker/)
2. Install Docker Compose as docker container:
    * MacOS X:
        * You should already have `docker-compose` installed.
    * Linux: 
        ```bash
         sudo curl -L --fail https://github.com/docker/compose/releases/download/1.29.2/run.sh -o /usr/local/bin/docker-compose
         sudo chmod +x /usr/local/bin/docker-compose
        ```


## Usage

Start database services:

```
docker-compose up -d
```

- PostgreSQL is running on port 5434
-  MySQL is running on port 3308


Shutdown databases:

```
docker-compose down -d
```

Consult the `docker-compose.yml` or `.env` files to get an idea how to connect to your favorite database.
