# groovy-cli-gradle-postgresql-trigger

## Description
Creates a small database table
called `dog` with an `insert update delete after` triggers.

All output normally
seen in a terminal will be in `java-srv/log` which will dump to the screen. The project may seem to hang but the logs from the container must be written to the project this can take up to 3 min.

## Tech stack
- groovy
- gradle
  - log4j
  - postgres driver

## Docker stack
- postgresql:alpine
- gradle:jdk11

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
