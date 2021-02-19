# Setup with docker

## Requirements:
- docker
- docker-compose

## Setup `docker-compose.yml`
```sh
wget -O docker-compose.yml https://raw.githubusercontent.com/paperbaseapp/paperbase/main/docker-compose.prod.yml
```
## Setup `.env`
```sh
wget -O .env https://github.com/paperbaseapp/paperbase/blob/main/.env.example
```
Adjust the values to fit your needs.
