# cnj-config-backend-micro

Cloud native Java backend based demonstrating application configuration with MP Config based on Eclipse MicroProfile.

## Status

![Build status](https://codebuild.eu-west-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiaFlDay9JdkEwcUYvbDhzc2Nsd0U0b0FzL096Tzc1NWZnZ3cybkxrRE1nd0lHTVM3N2JKUFNYeEhPaW9aRDYrVUZhUStPWDI0bXNVSVlVaW1wRXBUQXA0PSIsIml2UGFyYW1ldGVyU3BlYyI6IitGaUVTc1BralQreGZmaTgiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=main)

## Release Information

A changelog can be found in [changelog.md](changelog.md).

## Docker Pull Command

`docker pull docker.cloudtrain.aws.msgoat.eu/cloudtrain/cnj-config-backend-micro`

## Run this application

```shell 
docker run --name cnj-config-backend-micro -p 8080:8080 docker.cloudtrain.aws.msgoat.eu/cloudtrain/cnj-config-backend-micro
```

## Build this application

```shell 
mvn clean verify -P pre-commit-stage
```

Build results: a Docker image containing a Payara Micro application.
