# java-cli-maven-surefire-findbugs-jacoco-cucumber-junit-hello-world

## Description
Analyze source code for potential bugs.
A POC for maven app using JUnit5
and cucumber framework with jacoco
and surefire plugins.

## Tech stack
- java
- maven
	- findbugs
  - junit
  - jacoco
  - surefire
  - cucumber

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [Jacoco config](https://www.baeldung.com/jacoco)
