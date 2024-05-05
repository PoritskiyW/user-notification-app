<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Description

User notification app created using microservices

Built using NestJS, Redis, PostgreSQL.

# Requirements

NodeJS

NestJS CLI

Docker

Docker Compose

# Installation

```bash
$ git clone --recursive https://github.com/PoritskiyW/user-notification-app.git

$ docker compose build
```

# Running the app

```bash
$ docker compose up
```
# Updating the app

If any changes were made in this repository or submodules repositories run

```bash
$ git submodule update --remote
```

# ENV

.env files are needed to be located in the specific submodule directory.
Exact location of each .env can be found in docker-compose.yml
