# Greylog

## Liens
- https://go2docs.graylog.org/5-0/downloading_and_installing_graylog/docker_installation.htm
- https://github.com/Graylog2/docker-compose/tree/main/open-core

## Installation des images docker

```
docker pull graylog/graylog:5.1
docker pull mongo
docker pull opensearchproject/opensearch
docker pull docker.elastic.co/elasticsearch/elasticsearch:8.8.0
```

## Launch composition
docker compose up -d

## Remove composition
docker compose down

## Lifecycle
```
docker compose start
docker compose start graylog
docker compose stop
docker compose stop graylog
```

## Supervision
### Active containers
docker compose ps

### All containers (include stopped ones)
docker compose ps -a

## Logs
docker compose logs graylog

