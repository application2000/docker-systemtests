# Docker Systemtest image
[![](https://badge.imagelayers.io/yveshoppe/joomla-systemtests:latest.svg)](https://imagelayers.io/?images=yveshoppe/joomla-systemtests:latest 'Get your own badge on imagelayers.io')

Docker with LAMP setup, firefox and other tools for system tests with codeception.

Based on docker Ubuntu 16.04 image

Current image can also be found at dockerhub:

https://hub.docker.com/r/yveshoppe/joomla-systemtests/builds/

``docker pull yveshoppe/joomla-systemtests``

## Included software

* Apache 2.4
* MySQL 5.7
* PHP 7
* Composer (System wide)

### Gui Software

* Firefox
* Fluxbox and Xvfb (to run selenium tests)
