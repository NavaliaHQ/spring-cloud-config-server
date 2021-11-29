# spring-cloud-config-server

## Purpose
Spring Cloud Config Server provides an HTTP resource-based API for external configuration (name-value pairs or equivalent YAML content) in a distributed system.

## Requirements
jdk>=11

## Local Development
### run
add the following commands to your ~/.bashrc or ~/.zshrc
```
export GIT_USER=<gitlab user>
export GIT_PASSWORD=<gitlab password>
```

then run
`./gradlew bootRun`

### etc
This project uses gradle:

**Windows**: use gradlew.bat

**OSX**: use ./gradlew