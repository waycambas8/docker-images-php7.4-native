
# Haratago

Haratago is a travel, Hajj, Umrah and other trip booking application

## Environment

- Docker 3.1
- Docker Compose
- PHP 7.4
- MySql
- Phpmyadmin

## Deployment

To deploy this project run

```bash
  docker-compose --env-file .docker/.env.docker -f development-compose.yml up -d --build
```

