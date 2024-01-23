# Basic docker stack for Laravel project
It consists of the following:

- PHP
- Nginx
- MariaDB
- phpMyAdmin

## Installation

- Clone this repository on your local computer
- Configure .env as needed
- Run the `docker-compose up -d`.

```shell
git clone https://github.com/gumennikov2002/laradocker.git
cd laradocker/
cp .env.example .env
// modify .env.example as needed
docker-compose up -d
// visit localhost
```

Done! You can access it via `http://localhost:{port}`.

## Warning
This Docker Stack is build for local development and not for production usage.