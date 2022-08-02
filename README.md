# OpenSim-GUI Docker Image

## Build the image

```bash
docker-compose build
```

## Start OpenSim application

```bash
xhost +local:docker # Allow docker to access the X server
docker-compose up
```
