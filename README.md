# Linux Server

## Server Information

**IP Address:** 34.213.173.255

**URL:** http://34.213.173.255/

## Software Installed

### Server Software
  * Apache 2.4.18
  * libapache2-mod-wsgi 4.3.0.1
  * PostgreSQL 9.5
  * python-pip 8.1.1

### Python Application Dependencies
  * Flask 0.12.2
  * SQLAlchemy 1.1.13
  * Oauth2client 4.1.1
  * Requests 2.18.4

## Server Configurations
Ubuntu 16.04.3 LTS server instance created in Amazon Lightsail. Configured the uncomplicated firewall to deny all incoming requests from clients except to SSH port 2200, HTTP port 80, and NTP port 123. The default SSH port 22 and root login are disabled to enhance server security. Users won't be able to log in via password input and will need to have key-based authentication set up. The server is hosting a WSGI application [music/genre applicaton](http://34.213.173.255/) and uses PostgreSQL as its database.

## Resources
  * [How To Deploy a Flask Application on an Ubuntu VPS](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
  * [How To Install and Use PostgreSQL on Ubuntu 16.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-16-04)
