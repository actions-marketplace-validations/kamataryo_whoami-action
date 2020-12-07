# SANDBOX GitHub Actions

## Prerequisite

- install Docker
- `docker login` to your registry, with DockerHub as default

## build

```shell
# build your image
$ docker build --tag <username>/hello-gh-actions:latest .
# run your image
$ docker run -it <username>/hello-gh-actions:latest
# push your image
$ docker push <username>/hello-gh-actions:latest
# (optionnal) check hub.docker.com
$ open https://hub.docker.com/repository/docker/<username>/hello-gh-actions
```

