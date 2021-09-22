# itkmitl-static-web

## How to run with Docker Compose

```bash
docker-compose up --build
```

## How to run with Docker

```bash
# Build Docker Image
docker build -t drinker .

# Run
docker run --name drinker -p 8080:80 drinker
```

