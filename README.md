# GitHub Actions `@kamataryo/whoami`

My first GitHub Actions sandbox.

## Prerequisite

- install Docker
- `docker login` to your registry, with DockerHub as default

## build

```shell
# build your image
$ docker build --tag docker.io/<username>/whoami:latest .
# run your image
$ docker run -it docker.io/<username>/whoami:latest
# push your image
$ docker push docker.io/<username>/whoami:latest
# (optionnal) check hub.docker.com
$ open https://hub.docker.com/repository/docker/<username>/whoami
```
