Gradle Dockerfile
=================

Gradle Container to develop & build Java projects.

This repository contains **Dockerfile** of [Gradle](https://www.gradle.org/) for [Docker](https://www.docker.com/)'s 
[automated build](https://registry.hub.docker.com/u/lukin0110/gradle/) published to the public 
[Docker Hub Registry](https://registry.hub.docker.com/).

It uses [openjdk-8-jdk](http://openjdk.java.net/projects/jdk8/) and 
[Gradle 2.5](https://docs.gradle.org/2.5-rc-1/release-notes).

## Base Docker Image

* [java:8-jre](https://registry.hub.docker.com/_/java/)

## Pull the image
```
docker pull lukin0110/gradle
```

## Run
```
docker run -it --rm lukin0110/gradle
```

License
=======

    Copyright 2015 Maarten Huijsmans

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
