Dockerfiles 
===========

nginx-none-root
---------------

* using nginx:latest image
* running Nginx as user 101 on port 8080
* expose logs to /dev/stdout and /dev/stderr
* provides git, curl, wget tools, and bash

python-none-root
---------------

* using python:3.7.3-stretch image
* installs sphinx, boto, redis
* runs as appuser

see https://github.com/eumel8/dockerfiles
