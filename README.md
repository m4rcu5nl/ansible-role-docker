[![Build Status](https://travis-ci.org/m4rcu5nl/ansible-role-docker.svg?branch=develop)](https://travis-ci.org/m4rcu5nl/ansible-role-docker)    

docker-engine
=========

Ansible role to install Docker as discribed on [https://docs.docker.com/engine/installation/linux/centos/](https://docs.docker.com/engine/installation/linux/centos/).    

Currently only tested on a fresh DO Droplet running CentOS 7.

Role Variables
--------------

### dockerengine_state
Determines the state this role leaves the docker service in when it's done. (started|stopped)    
Default: started

### dockerengine_enabled
Determines if the docker service should be enabled. (yes|no)    
Default: yes
