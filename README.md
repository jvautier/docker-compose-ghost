# docker-compose ghost

Docker-compose stack with [ghost](https://ghost.org/)

## Requirements

- [docker-compose](https://docs.docker.com/compose/)

## Usages

Ghost version is driven by the [.env](.env) file with another variables.



```sh
docker-compose up -d
```

```sh
docker-compose logs -f
```

```sh
docker-compose logs -f ghost
```

export COMPOSE_FILE=docker-compose.traefik.yml
protocol=http host=localhost port=80 docker-compose up 
docker app install
docker app uninstall
docker app status
