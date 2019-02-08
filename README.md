# Project Title

Item Catalog Linux Server Configuration

Using an Amazon Light Sail server, configure it to run an apache web server running a flask python application with a postgresql database:

## Configurations

The Amazon Light Sail server has been configured in the following manor:

1. All packages have been updated/upgraded on the server
2. The firewall (UFW) has been configured in the following manor:
    1. SSH Port 2200 (Port 22 Denied)
    2. HTTP Port 80
    3. NTP Port 123
3. Root user login disabled
4. User 'grader' created
    1. Given 'grader' sudo permissions
    2. login only permitted using key
5. TimeZone configured to local time

## Accessing the Web App

Below is the IP Address/URL of the web application

http://34.213.151.69.xip.io

## Third Party Software Installed

1. Apache 2 HTTP Server
2. Postgresql for database management
3. Mod-wsgi Apache2 module providing an interface for python based web apps
4. Python libraries for running the flask web app
    1. Flask
    2. SqlAlchemy
    3. oauth2client
    4. httplib2
    5. requests
    6. passlib

## Versioning

Version 1.0

## Authors

- **Mitchell Cook**
