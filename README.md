
# WordPress Local Development Environment

WordPress local Development Environment using 
- docker
- docker-compose
- mysql:8.0
- phpmyadmin
- mailhog
- wordpress:latest




## Installation

Prerequisites
- docker

First clone this repository
```bash
  git clone git@github.com:asifthewebguy/WordPress-local-Dev.git
  cd WordPress-local-Dev
```

rename the `.env.example` file to `.env` and update the values as needed

```bash
  mv .env.example .env
```

update .env according to your needs

```bash
  nano .env
```
or 
```bash
  nvim .env
```

To start the docker stack
```bash
docker-compose up -d
```

To terminate it
```bash
docker-compose down
```

