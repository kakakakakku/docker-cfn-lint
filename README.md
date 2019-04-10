# docker-cfn-lint

[![Docker Pulls](https://img.shields.io/docker/pulls/kakakakakku/cfn-lint.svg?style=for-the-badge)](https://hub.docker.com/r/kakakakakku/cfn-lint/)
[![Docker Automated build](https://img.shields.io/docker/automated/kakakakakku/cfn-lint.svg?style=for-the-badge)](https://hub.docker.com/r/kakakakakku/cfn-lint/)

Dockerized CloudFormation Linter (cfn-lint)

## Usage

```sh
$ docker pull kakakakakku/cfn-lint
$ docker run -v ${PWD}:/templates -it kakakakakku/cfn-lint -t "templates/*.yaml"
```

## Supported versions

- v0.17.1 (latest)
- v0.18.1
