[![Docker Image Size (latest by date)](https://img.shields.io/docker/image-size/downey/mando)](https://hub.docker.com/repository/docker/downey/mando) [![Docker Image Version (latest by date)](https://img.shields.io/docker/v/downey/mando)](https://hub.docker.com/repository/docker/downey/mando)


# mando
> [this is the way](https://youtu.be/uelA7KRLINA?t=8)

just a little app for testing path-based routing

```
docker run -p 8080:8080 downey/mando
```

## build and deploy

can be built and deployed to Kubernetes with [`kbld`](https://get-kbld.io/)

```console
kbld -f build -f deploy | kubectl apply -f -
```
