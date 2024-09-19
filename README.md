# Spring Boot Admin by [codecentric](https://codecentric.de)
[![Apache License 2](https://img.shields.io/badge/license-ASF2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0.txt)
![Build Status](https://github.com/codecentric/spring-boot-admin/actions/workflows/build-main.yml/badge.svg?branch=master)
[![codecov](https://codecov.io/gh/codecentric/spring-boot-admin/branch/master/graph/badge.svg?token=u5SWsZpj5S)](https://codecov.io/gh/codecentric/spring-boot-admin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/de.codecentric/spring-boot-admin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/de.codecentric/spring-boot-admin/)
[![Gitter](https://badges.gitter.im/codecentric/spring-boot-admin.svg)](https://gitter.im/codecentric/spring-boot-admin?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

* goal
  * UI for [Spring Boot <sup>®</sup>](http://projects.spring.io/spring-boot/ "Official Spring-Boot website") web applications / expose actuator endpoints
    * if you want to monitor Python applications -> use [Pyctuator](https://github.com/SolarEdgeTech/pyctuator) 
* community project

## Compatibility Matrix

| Spring Boot Version | Spring Boot Admin Server App|
|---------------------|-------------------|
| 2.7                 | 2.7.Y             |
| 3.0                 | 3.0.Y             |
| ...                 | ...               |
| 3.3                 | 3.3.Y             |

* independently of the underlying Spring Boot version -> you can monitor it
  * _Example:_ if you run Spring Boot Admin Server v2.6 & monitor a service / Spring Boot v2.3 + Spring Boot Admin Client v2.3 -> it's possible

## Getting Started

* [A quick guide](https://docs.spring-boot-admin.com/current/getting-started.html)
* YouTube videos
  * [**Cloud Native Spring Boot® Admin by Johannes Edmeier @ Spring I/O 2019**](https://youtu.be/Ql1Gnz4L_-c)
  * [**Monitoring Spring Boot® Applications with Spring Boot Admin @ Spring I/O 2018**](https://youtu.be/__zkypwjSMs) 
  * [**Spring Boot® Admin - Monitoring and Configuring Spring Boot Applications at Runtime**](https://goo.gl/2tRiUi)

## Getting Help

Having trouble with codecentric's Spring Boot Admin? We’d like to help!

 * Check the [reference documentation](http://codecentric.github.io/spring-boot-admin/current/).

 * Ask a question on [stackoverflow.com](http://stackoverflow.com/questions/tagged/spring-boot-admin) - we monitor questions tagged with `spring-boot-admin`.

 * Ask for help in our [spring-boot-admin Gitter chat](https://gitter.im/codecentric/spring-boot-admin)

 * Report bugs at http://github.com/codecentric/spring-boot-admin/issues.

## Reference Guide

### Translated versions
The following reference guides have been translated by users of Spring Boot Admin and are not part of the official bundle.
The maintainers of Spring Boot Admin will not update and maintain the guides mentioned below.

[Version 2.6.6 (Chinese translated by @qq253498229)](https://consolelog.gitee.io/docs-spring-boot-admin-docs-chinese/)

## Trademarks and licenses
The source code of codecentric's Spring Boot Admin is licensed under [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

Spring, Spring Boot and Spring Cloud are trademarks of [Pivotal Software, Inc.](https://pivotal.io/) in the U.S. and other countries.

## Snapshot builds

* add `repositories` | "settings.xml"

    ```xml
    <repository>
        <id>sba-snapshot</id>
        <name>Spring Boot Admin Snapshots</name>
        <url>https://maven.pkg.github.com/codecentric/spring-boot-admin</url>
        <snapshots>
            <enabled>true</enabled>
        </snapshots>
        <releases>
            <enabled>false</enabled>
        </releases>
    </repository>
    ```

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md) file.
