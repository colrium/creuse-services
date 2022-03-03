# Deployment

## Create network

```console
docker network create proxy-manager
```

## Run

### Development

```console
docker-compose -f docker-compose.dev.yml up -d --build
```

### Production

```console
docker-compose up -d
```
