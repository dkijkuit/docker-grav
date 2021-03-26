## Building the image from Dockerfile

```
docker build -t grav:latest .
```
## Running Grav Image with docker-compose and a volume mapped to a local directory

```docker-compose up -d```

In the current directory a subdirectory `grav` is created where the container files are mounted (after start).