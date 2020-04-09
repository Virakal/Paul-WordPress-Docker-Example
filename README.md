# WordPress Docker Compose example

## Setup

- Change .env passwords and stuff in `.env` file if you want.
- Change port 8080 to whatever port you want to be on.
- Copy any extra plugins into your image by changing `./wordpress/Dockerfile`.

## Run

Just run `docker-compose up`. Use `docker-compose up -d` to do it in the background and `docker-compose down` to bring everything down.
