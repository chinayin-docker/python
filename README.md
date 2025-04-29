# Python Base Image

[![Docker Image CI](https://github.com/chinayin-docker/python/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/chinayin-docker/python/actions/workflows/ci.yml)
![Docker Image Version (latest semver)](https://img.shields.io/docker/v/chinayin/python?sort=semver)
![Docker Image Size (latest semver)](https://img.shields.io/docker/image-size/chinayin/python?sort=semver)
![Docker Pulls](https://img.shields.io/docker/pulls/chinayin/python)

Docker Image packaging for Python

### Supported tags and respective `Dockerfile` links

![](https://img.shields.io/docker/v/chinayin/python/3.12)
![](https://img.shields.io/docker/v/chinayin/python/3.12-debian)
![](https://img.shields.io/docker/v/chinayin/python/3.12-alpine)

### Image Variants

- `python:<version>`
- `python:<version>-debian`
- `python:<version>-alpine`

### Use Python

You can use the image directly, e.g.

```
docker run --rm -it chinayin/python:3.12-debian
```

The images are built daily and have the security release enabled, so will contain any security updates released more
than 24 hours ago.

You can also use the images as a base for your own Dockerfile:

```
FROM chinayin/python:3.12-debian
```

