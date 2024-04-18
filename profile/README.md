> **Note**: 
> Previously known as https://github.com/libreoffice-docker

## About

The LibreOffice with unoserver on Docker

### Pre-built image

[![Release](https://github.com/libreofficedocker/libreoffice-unoserver/actions/workflows/release.yml/badge.svg?branch=v2)](https://github.com/libreofficedocker/libreoffice-unoserver/actions/workflows/release.yml)
[![Test](https://github.com/libreofficedocker/libreoffice-unoserver/actions/workflows/test.yml/badge.svg)](https://github.com/libreofficedocker/libreoffice-unoserver/actions/workflows/test.yml)
[![Docker Pulls](https://img.shields.io/docker/pulls/libreofficedocker/libreoffice-unoserver)](https://hub.docker.com/r/libreofficedocker/libreoffice-unoserver)

This image uses the [`alpine`](https://hub.docker.com/_/alpine) as base images.

> **Note**
>
> You can find the pre-built images on [Docker Hub](https://hub.docker.com/u/libreofficedocker).
> All release are built following Alpine release versions and only the last 10 versions are built.

```
docker pull libreofficedocker/libreoffice-unoserver:${ALPINE_VERSION}
```

> [!NOTE]
> The container images are being build and pushed to the registry periodically through an automated process. It schedules a build every week to ensure that the images are up-to-date with the latest security patches and updates.
>
> Runs at 00:00, only on Saturday every week.

### REST API

This image shipped with REST API for unoserver by default.

See https://github.com/libreofficedocker/unoserver-rest-api for more information.

> **Warning**
>
> It is important to know that the  REST API layer DOES NOT provide any type of security whatsoever.
> It is NOT RECOMMENDED to expose this container image to the internet.

## License

Licensed under [Apache-2.0 license](LICENSE)
