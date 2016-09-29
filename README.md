# LinuxServerConfiguration

Repository for the Linux Configuration Project for Udacity's Nanodegree

IP Address: http://54.71.217.44/
SSH Port: 2200

Software Installed:

* Pip
* Finger
* Apache
* mod_wsgi
* postgresql
* Flask
* SQLAlchemy
* Oauth2client

Configuration Changes:

* Create new user 'grader'
* Give the 'grader' user permission to sudo
* Update packages throug sudo apt-get update & sudo apt-get upgrade
* Changed SSH port to 2200 through the configuration file
* Configured UFW as instructed in the Project Details and enabled it
* Configured local timezone to UTC
* Installed and configured Apache and mod_wsgi
* Install and configure postgresql
* Clone git repository with Item Catalog project and configure it to serve on port 80 for the IP Address of the AWS instance
