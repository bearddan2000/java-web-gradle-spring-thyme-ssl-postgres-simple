# java-web-gradle-spring-thyme-ssl-postgres-simple

## Description
A thyme springboot java gradle build,
that connects to postgres database.

Uses self-sign ssl.

## Tech stack
- springboot
  - web
- thymeleaf
- gradle
  - 6.8.2
- bootstrap
- jquery
- dataTable

## Docker stack
- alpine:edge
- postgres
- gradle:jdk11

## To run
`sudo ./install.sh -u`
Available http://localhost

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
