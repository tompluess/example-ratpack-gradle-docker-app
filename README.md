This is an example Ratpack app that:

1. Is implemented in Java
2. Use Guice for dependency injection
3. Uses the `ratpack` Gradle plugin
4. Builds a docker image using the Gradle Docker plugin `docker-java-application`  

## Getting Started

Check this project out, cd into the directory and run:

    ./gradlew run

This will start the ratpack app in a development mode. In your browser go to `http://localhost:5050`.

Building a docker image and running it can be done with the following commands:

    ./gradlew dockerBuildImage
    docker images # just for information
    docker run --rm -it skyr.ch/ratpack
    # the running server must be terminated with Ctrl-C


## More on Docker

* Visit https://www.docker.com
* Docker Gradle Plugin: https://github.com/bmuschko/gradle-docker-plugin


## More on Ratpack

To learn more about Ratpack, visit http://www.ratpack.io
