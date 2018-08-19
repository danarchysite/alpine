# dAnarchy Image

Custom alpine docker custom image

## Build the image

```
docker build -t danarchy/alpine:latest .
```

## Run a container

```
docker run -t -i -h image --name image --rm -e ENV_USER_UID=`id -u` danarchy/alpine:latest /bin/bash -l
```