# Run Elastic Search and Kibana with Docker

详见: [在 Docker 中运行 ElasticSearch](https://hansimov.github.io/blog/notes/elastic-search.html#在-docker-中运行-elasticsearch)

## Config

Modify `.env`: `ELASTIC_PASSWORD`, `KIBANA_PASSWORD`, `STACK_VERSION`, `ES_PORT`, `KIBANA_PORT`

## Commands

Build and run services:

```sh
docker compose build && docker compose down && docker compose up
```

Remove services only:

```sh
docker compose down
```