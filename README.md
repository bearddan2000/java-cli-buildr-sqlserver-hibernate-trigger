# java-cli-buildr-sqlserver-hibernate-trigger

## Description
Creates a small database table
called `dog` and populates with hql.

Added an insert trigger to `dog`.

## Tech stack
- java
- buildr
  - hibernate
  - hql
  - log4j
  - sqlserver driver

## Docker stack
- vanto/apache-buildr:latest-jruby-jdk8
- mcr.microsoft.com/mssql/server:2017-latest-ubuntu

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
