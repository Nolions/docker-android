# docker-android

Build Android environment's image

## build docker image

```bash
docker build -t <image_name> .
```

## use

```bash
docker run -d -t android:<jdk_version> /bin/bash
```

***jdk 11***

```bash
docker run -d -t android:jdk11 /bin/bash
```

***jdk 8***

```bash
docker run -d -t android:jdk11 /bin/bash
```