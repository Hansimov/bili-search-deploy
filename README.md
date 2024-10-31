# Bili-Search-Deploy
Deploy backend, frontend and website of Bili Search

## Commands

Recommended:

```sh
docker compose build && docker compose down && docker compose up
```

Shorter:

```sh
docker compose down && docker compose up --build
```

## Clear commands

Stop conainers:

```sh
docker stop $(docker ps -aq)
```

Remove containers:

```sh
docker rm $(docker ps -aq)
```

Remove images:

```sh
docker rmi $(docker images -q)
```

Prune docker networks:

```sh
docker network prune -f
```

Clear build cache of intermediate layers:

```sh
docker builder prune -a --force
```

Restart daemon:

```sh
sudo systemctl restart docker
```
