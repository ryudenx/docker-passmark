# docker-passmark

## Run

### Ubuntu base

```
docker build -t ryudenx/passmark-ubuntu:latest https://github.com/ryudenx/docker-passmark.git -f Dockerfile_Ubuntu
docker run --rm -it --privileged ryudenx/passmark-ubuntu:latest
```

### Rocky Linux base

```
docker build -t ryudenx/passmark-rocky:latest https://github.com/ryudenx/docker-passmark.git -f Dockerfile_Rocky
docker run --rm -it --privileged ryudenx/passmark-rocky:latest
```
