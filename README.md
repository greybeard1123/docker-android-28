# docker-android-28

[![Docker Status][docker-shield]][docker-link] [![Docker Pulls][pulls-shield]][pulls-link] [![Layers][layers-shield]][layers-link] [![Version][version-shield]][version-link]

A minimal android [Docker](https://www.docker.com/) image based on Ubuntu Linux

## Content &nbsp;

- Ubuntu ( **16.04** )
- Oracle Java 8
- Android platform tools ( **3952940** )
- Android SDK ( **API 28** )
- Android SDK Build-Tools ( **28.0.3** )
- Google Repository ( **latest** )
- Android SDK Tools ( **latest** )
- Android SDK Platform-Tools ( **latest** )
- Android Support Repository ( **latest** )

## Use this &nbsp;>

### as base image

exactly as you would with any other docker image inside `Dockerfile`

```Dockerfile
FROM greybeard1123/docker-android-28
```

### as pull from Docker Hub

```sh
$ docker pull greybeard1123/docker-android-28
```

### as local build

```sh
$ git clone https://github.com/greybeard1123/docker-android-28.git && cd docker-android-28 
$ docker build --no-cache -t greybeard1123/docker-android-28 .
```

### as running container

```sh
$ docker run --rm -it greybeard1123/docker-android-28
```

[docker-shield]: https://img.shields.io/docker/build/greybeard1123/docker-android-28.svg
[docker-link]: https://hub.docker.com/r/greybeard1123/docker-android-28

[pulls-shield]: https://img.shields.io/docker/pulls/greybeard1123/docker-android-28.svg
[pulls-link]: https://hub.docker.com/r/greybeard1123/docker-android-28

[layers-shield]: https://images.microbadger.com/badges/image/greybeard1123/docker-android-28.svg
[layers-link]: https://microbadger.com/images/greybeard1123/docker-android-28

[version-shield]: https://images.microbadger.com/badges/version/greybeard1123/docker-android-28.svg
[version-link]: https://microbadger.com/images/greybeard1123/docker-android-28
