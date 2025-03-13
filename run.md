# Project configuration

## Run
To build a project, type `maven package`<br>
To run a project, type: `java -jar /target/<jar_name>.jar`<br>
*where `<jar_name>` is value of `jar.finalName` in `<properties>` tag of your `pom.xml`*

## Docker
To create Docker Image, type: `docker build --tag passgo-img-backend .`<br>
To run project in Docker, type: `docker run --name passgo-backend -p 8080:8080 -d passgo-img-backend`

## What's next?
- [x] Create backend Dockerfile
- [ ] Create frontend Dockerfile
- [ ] Create db Dockerfile
- [ ] Create docker-compose file
---