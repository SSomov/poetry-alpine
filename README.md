# Python Alpine Poetry Docker Image
[![GitHub last commit](https://img.shields.io/github/last-commit/SSomov/python-alpine-poetry)](https://github.com/SSomov/python-alpine-poetry)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/avt0x/python-alpine-poetry/latest)

[Poetry](https://python-poetry.org/docs/) is a tool for
**dependency management** and **packaging** in Python.

This repository provides a lightweight alpine-based container image with _Poetry_ preinstalled.


### Build

```docker build . -t poetry:latest```

### Version Poetry

```docker run -it poetry```

### DockerHub

```docker pull avt0x/poetry:latest```

### Using

```FROM avt0x/poetry:latest```