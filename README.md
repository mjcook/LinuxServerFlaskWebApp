# Project Title

Item Catalog Linux Server Configuration

Using an Amazon Light Sail server, configure it to run an apache web server running a flask python application with a postgresql database:

## Configurations

The Amazon Light Sail server has been configured in the following manor:

1. All packages have been updated/upgraded on the server
2. The firewall (UFW) has been configured in the following manor:
    1. SSH Port 2200 (Port 22 Removed)
    2. HTTP Port 80
    3. NTP Port 123
3. Root user login disabled
4. User 'grader' created
    1. Given 'grader' sudo permissions
    2. login only permitted using key
5. TimeZone configured to local time
6. Apache2 and mod-wsgi installed to run web app
7. Postgresql installed and database created
8. Git installed to pull in flask Item Catalog web app
    1. Python libraries used in Item Catalog installed with pip

## Accessing the Web App

Below is the IP Address/URL of the web application

http://34.213.151.69.xip.io

## Versioning

Version 1.0

## Authors

- **Mitchell Cook**
