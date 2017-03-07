[![Build Status](https://travis-ci.org/m4rcu5nl/ansible-role-docker.svg?branch=master)](https://travis-ci.org/m4rcu5nl/ansible-role-docker) [![GitHub issues](https://img.shields.io/github/issues/m4rcu5nl/ansible-role-docker.svg)](https://github.com/m4rcu5nl/ansible-role-docker/issues) 

docker-engine
=========

Ansible role to install Docker as discribed on [https://docs.docker.com/engine/installation/linux/centos/](https://docs.docker.com/engine/installation/linux/centos/).    

Additionally installs docker-compose version 1.9.0 using Pip to maintain compatibility with Ansible.

Role Variables
--------------

### dockerengine_state
Determines the state this role leaves the docker service in when it's done. (started|stopped)    
Default: started

### dockerengine_enabled
Determines if the docker service should be enabled. (yes|no)    
Default: yes
