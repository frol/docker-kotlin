[![Docker Build Status](https://github.com/DRSchlaubi/docker-kotlin/actions/workflows/release.yaml/badge.svg)](https://github.com/DRSchlaubi/docker-kotlin/actions/workflows/release.yaml) [![Docker Pulls](https://img.shields.io/docker/pulls/schlaubiboy/kotlin)](https://hub.docker.com/r/schlaubiboy/kotlin/)

# Contents
- [Image Variants](#image-variants)
- [What is Kotlin?](#what-is-kotlin)
- [Usage](#usage)
- [Reference](#reference)
- [Versions](#supported-tags-and-respective-dockerfile-links)

### Image Variants
Each image gets build for 3 JDK versions JDK8, JDK11 and JDK16 (or the latest release at the time of publishing the image).
For each JDK version 4 different base images are used: oracle, debian, alpine, alpineslim

Therefore, the tag names are structured in this way:
schlaubiboy/kotlin:<kotlin-version>-jdk\<version>-\<os>

The default jdk version is always the latest at the time of publishing the image so right not it is 16

The default os is oracle so unlike other os images the oracle image is called `schlaubiboy/kotlin:<kotlin-version>-jdk<version>`


### What is Kotlin?

Kotlin is a statically-typed programming language that runs on the Java virtual machine and also can be compiled to JavaScript source code or use the LLVM compiler infrastructure. Its primary development is from a team of JetBrains programmers based in Saint Petersburg, Russia. While the syntax is not compatible with Java, Kotlin is designed to interoperate with Java code and is reliant on Java code from the existing Java Class Library, such as the collections framework.

See https://en.wikipedia.org/wiki/Kotlin_%28programming_language%29 for more information.

![Kotlin Logo](https://github.com/DRSchlaubi/docker-kotlin/raw/main/Kotlin-logo.png)

### Usage

Start using the Kotlin REPL : `docker container run -it --rm schlaubiboy/kotlin`

See Kotlin compiler version : `docker container run -it --rm schlaubiboy/kotlin kotlinc -version`

See Kotlin compiler help : `docker container run -it --rm schlaubiboy/kotlin kotlinc -help`

### Reference

* Kotlin website : https://kotlinlang.org

* Where to file issues : https://github.com/DRSchlaubi/docker-kotlin/issues

* Maintained by : https://schlau.bi

### Supported tags and respective `Dockerfile` links

#### Versions
- [1.5.30](#1530)
- [1.5.30-RC](#1530-rc)
- [1.5.30-M1](#1530-m1)
- [1.5.21](#1521)
- [1.5.20](#1520)
- [1.5.20-RC](#1520-rc)
- [1.5.20-M1](#1520-m1)
- [1.5.10](#1510)
- [1.5.0](#150)
- [1.5.0-RC](#150-rc)
- [1.5.0-M2](#150-m2)
- [1.4.32](#1432)

### 1.5.30
- `1.5.30`, `1.5.30-jdk16`, `1.5.30-jdk11`, `1.5.30-jdk8` [oracle/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/oracle/Dockerfile) Based on openjdk `-oracle` tags
- `1.5.30`, `1.5.30-jdk16-alpine`, `1.5.30-jdk11-alpine`, `1.5.30-jdk8-alpine` [alpine/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/alpine/Dockerfile) Based on adoptopenjdk `alpine` tags
- `1.5.30`, `1.5.30-jdk16-debian`, `1.5.30-jdk11-debian`, `1.5.30-jdk8-debian` [debian/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/debian/Dockerfile) Based on adoptopenjdk `debian` tags
- `1.5.30`, `1.5.30-jdk16-slim`, `1.5.30-jdk11-slim`, `1.5.30-jdk8-slim` [slim/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/slim/Dockerfile) Based on adoptopenjdk `alpineslim` tags
### 1.5.30-RC
- `1.5.30-RC`, `1.5.30-RC-jdk16`, `1.5.30-RC-jdk11`, `1.5.30-RC-jdk8` [oracle/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/oracle/Dockerfile) Based on openjdk `-oracle` tags
- `1.5.30-RC`, `1.5.30-RC-jdk16-alpine`, `1.5.30-RC-jdk11-alpine`, `1.5.30-RC-jdk8-alpine` [alpine/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/alpine/Dockerfile) Based on adoptopenjdk `alpine` tags
- `1.5.30-RC`, `1.5.30-RC-jdk16-debian`, `1.5.30-RC-jdk11-debian`, `1.5.30-RC-jdk8-debian` [debian/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/debian/Dockerfile) Based on adoptopenjdk `debian` tags
- `1.5.30-RC`, `1.5.30-RC-jdk16-slim`, `1.5.30-RC-jdk11-slim`, `1.5.30-RC-jdk8-slim` [slim/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/slim/Dockerfile) Based on adoptopenjdk `alpineslim` tags
### 1.5.30-M1
- `1.5.30-M1`, `1.5.30-M1-jdk16`, `1.5.30-M1-jdk11`, `1.5.30-M1-jdk8` [oracle/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/oracle/Dockerfile) Based on openjdk `-oracle` tags
- `1.5.30-M1`, `1.5.30-M1-jdk16-alpine`, `1.5.30-M1-jdk11-alpine`, `1.5.30-M1-jdk8-alpine` [alpine/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/alpine/Dockerfile) Based on adoptopenjdk `alpine` tags
- `1.5.30-M1`, `1.5.30-M1-jdk16-debian`, `1.5.30-M1-jdk11-debian`, `1.5.30-M1-jdk8-debian` [debian/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/debian/Dockerfile) Based on adoptopenjdk `debian` tags
- `1.5.30-M1`, `1.5.30-M1-jdk16-slim`, `1.5.30-M1-jdk11-slim`, `1.5.30-M1-jdk8-slim` [slim/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/slim/Dockerfile) Based on adoptopenjdk `alpineslim` tags
### 1.5.21
- `1.5.21`, `1.5.21-jdk16`, `1.5.21-jdk11`, `1.5.21-jdk8` [oracle/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/oracle/Dockerfile) Based on openjdk `-oracle` tags
- `1.5.21`, `1.5.21-jdk16-alpine`, `1.5.21-jdk11-alpine`, `1.5.21-jdk8-alpine` [alpine/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/alpine/Dockerfile) Based on adoptopenjdk `alpine` tags
- `1.5.21`, `1.5.21-jdk16-debian`, `1.5.21-jdk11-debian`, `1.5.21-jdk8-debian` [debian/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/debian/Dockerfile) Based on adoptopenjdk `debian` tags
- `1.5.21`, `1.5.21-jdk16-slim`, `1.5.21-jdk11-slim`, `1.5.21-jdk8-slim` [slim/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/slim/Dockerfile) Based on adoptopenjdk `alpineslim` tags
### 1.5.20
- `1.5.20`, `1.5.20-jdk16`, `1.5.20-jdk11`, `1.5.20-jdk8` [oracle/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/oracle/Dockerfile) Based on openjdk `-oracle` tags
- `1.5.20`, `1.5.20-jdk16-alpine`, `1.5.20-jdk11-alpine`, `1.5.20-jdk8-alpine` [alpine/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/alpine/Dockerfile) Based on adoptopenjdk `alpine` tags
- `1.5.20`, `1.5.20-jdk16-debian`, `1.5.20-jdk11-debian`, `1.5.20-jdk8-debian` [debian/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/debian/Dockerfile) Based on adoptopenjdk `debian` tags
- `1.5.20`, `1.5.20-jdk16-slim`, `1.5.20-jdk11-slim`, `1.5.20-jdk8-slim` [slim/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/slim/Dockerfile) Based on adoptopenjdk `alpineslim` tags
### 1.5.20-RC
- `1.5.20-RC`, `1.5.20-RC-jdk16`, `1.5.20-RC-jdk11`, `1.5.20-RC-jdk8` [oracle/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/oracle/Dockerfile) Based on openjdk `-oracle` tags
- `1.5.20-RC`, `1.5.20-RC-jdk16-alpine`, `1.5.20-RC-jdk11-alpine`, `1.5.20-RC-jdk8-alpine` [alpine/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/alpine/Dockerfile) Based on adoptopenjdk `alpine` tags
- `1.5.20-RC`, `1.5.20-RC-jdk16-debian`, `1.5.20-RC-jdk11-debian`, `1.5.20-RC-jdk8-debian` [debian/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/debian/Dockerfile) Based on adoptopenjdk `debian` tags
- `1.5.20-RC`, `1.5.20-RC-jdk16-slim`, `1.5.20-RC-jdk11-slim`, `1.5.20-RC-jdk8-slim` [slim/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/slim/Dockerfile) Based on adoptopenjdk `alpineslim` tags
### 1.5.20-M1
- `1.5.20-M1`, `1.5.20-M1-jdk16`, `1.5.20-M1-jdk11`, `1.5.20-M1-jdk8` [oracle/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/oracle/Dockerfile) Based on openjdk `-oracle` tags
- `1.5.20-M1`, `1.5.20-M1-jdk16-alpine`, `1.5.20-M1-jdk11-alpine`, `1.5.20-M1-jdk8-alpine` [alpine/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/alpine/Dockerfile) Based on adoptopenjdk `alpine` tags
- `1.5.20-M1`, `1.5.20-M1-jdk16-debian`, `1.5.20-M1-jdk11-debian`, `1.5.20-M1-jdk8-debian` [debian/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/debian/Dockerfile) Based on adoptopenjdk `debian` tags
- `1.5.20-M1`, `1.5.20-M1-jdk16-slim`, `1.5.20-M1-jdk11-slim`, `1.5.20-M1-jdk8-slim` [slim/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/slim/Dockerfile) Based on adoptopenjdk `alpineslim` tags
### 1.5.10
- `1.5.10`, `1.5.10-jdk16`, `1.5.10-jdk11`, `1.5.10-jdk8` [oracle/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/oracle/Dockerfile) Based on openjdk `-oracle` tags
- `1.5.10`, `1.5.10-jdk16-alpine`, `1.5.10-jdk11-alpine`, `1.5.10-jdk8-alpine` [alpine/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/alpine/Dockerfile) Based on adoptopenjdk `alpine` tags
- `1.5.10`, `1.5.10-jdk16-debian`, `1.5.10-jdk11-debian`, `1.5.10-jdk8-debian` [debian/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/debian/Dockerfile) Based on adoptopenjdk `debian` tags
- `1.5.10`, `1.5.10-jdk16-slim`, `1.5.10-jdk11-slim`, `1.5.10-jdk8-slim` [slim/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/slim/Dockerfile) Based on adoptopenjdk `alpineslim` tags
### 1.5.0
- `1.5.0`, `1.5.0-jdk16`, `1.5.0-jdk11`, `1.5.0-jdk8` [oracle/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/oracle/Dockerfile) Based on openjdk `-oracle` tags
- `1.5.0`, `1.5.0-jdk16-alpine`, `1.5.0-jdk11-alpine`, `1.5.0-jdk8-alpine` [alpine/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/alpine/Dockerfile) Based on adoptopenjdk `alpine` tags
- `1.5.0`, `1.5.0-jdk16-debian`, `1.5.0-jdk11-debian`, `1.5.0-jdk8-debian` [debian/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/debian/Dockerfile) Based on adoptopenjdk `debian` tags
- `1.5.0`, `1.5.0-jdk16-slim`, `1.5.0-jdk11-slim`, `1.5.0-jdk8-slim` [slim/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/slim/Dockerfile) Based on adoptopenjdk `alpineslim` tags
### 1.5.0-RC
- `1.5.0-RC`, `1.5.0-RC-jdk16`, `1.5.0-RC-jdk11`, `1.5.0-RC-jdk8` [oracle/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/oracle/Dockerfile) Based on openjdk `-oracle` tags
- `1.5.0-RC`, `1.5.0-RC-jdk16-alpine`, `1.5.0-RC-jdk11-alpine`, `1.5.0-RC-jdk8-alpine` [alpine/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/alpine/Dockerfile) Based on adoptopenjdk `alpine` tags
- `1.5.0-RC`, `1.5.0-RC-jdk16-debian`, `1.5.0-RC-jdk11-debian`, `1.5.0-RC-jdk8-debian` [debian/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/debian/Dockerfile) Based on adoptopenjdk `debian` tags
- `1.5.0-RC`, `1.5.0-RC-jdk16-slim`, `1.5.0-RC-jdk11-slim`, `1.5.0-RC-jdk8-slim` [slim/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/slim/Dockerfile) Based on adoptopenjdk `alpineslim` tags
### 1.5.0-M2
- `1.5.0-M2`, `1.5.0-M2-jdk16`, `1.5.0-M2-jdk11`, `1.5.0-M2-jdk8` [oracle/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/oracle/Dockerfile) Based on openjdk `-oracle` tags
- `1.5.0-M2`, `1.5.0-M2-jdk16-alpine`, `1.5.0-M2-jdk11-alpine`, `1.5.0-M2-jdk8-alpine` [alpine/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/alpine/Dockerfile) Based on adoptopenjdk `alpine` tags
- `1.5.0-M2`, `1.5.0-M2-jdk16-debian`, `1.5.0-M2-jdk11-debian`, `1.5.0-M2-jdk8-debian` [debian/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/debian/Dockerfile) Based on adoptopenjdk `debian` tags
- `1.5.0-M2`, `1.5.0-M2-jdk16-slim`, `1.5.0-M2-jdk11-slim`, `1.5.0-M2-jdk8-slim` [slim/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/slim/Dockerfile) Based on adoptopenjdk `alpineslim` tags
### 1.4.32
- `1.4.32`, `1.4.32-jdk16`, `1.4.32-jdk11`, `1.4.32-jdk8` [oracle/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/oracle/Dockerfile) Based on openjdk `-oracle` tags
- `1.4.32`, `1.4.32-jdk16-alpine`, `1.4.32-jdk11-alpine`, `1.4.32-jdk8-alpine` [alpine/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/alpine/Dockerfile) Based on adoptopenjdk `alpine` tags
- `1.4.32`, `1.4.32-jdk16-debian`, `1.4.32-jdk11-debian`, `1.4.32-jdk8-debian` [debian/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/debian/Dockerfile) Based on adoptopenjdk `debian` tags
- `1.4.32`, `1.4.32-jdk16-slim`, `1.4.32-jdk11-slim`, `1.4.32-jdk8-slim` [slim/Dockerfile](https://github.com/DRSchlaubi/docker-kotlin/blob/main/slim/Dockerfile) Based on adoptopenjdk `alpineslim` tags


### 1.4.20 and earlier
For 1.4 and earlier please check this repository: https://github.com/Zenkikat/docker-kotlin
