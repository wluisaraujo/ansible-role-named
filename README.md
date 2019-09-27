[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-DNS%20Server-blue.svg)](https://galaxy.ansible.com/wluisaraujo/named) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-named.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-named) 

#[![Docker Pulls](https://img.shields.io/badge/docker%20pulls-docker%20pulls-lightgrey)](https://hub.docker.com/r/wluisaraujo/bind9/)

[![Docker Pulls](https://img.shields.io/docker/pulls/jenkins/jenkins.svg)](https://hub.docker.com/r/wluisaraujo/bind9/)

# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Named Server](https://www.isc.org/downloads/bind/)

------------

Description
------------

 * Administrar um servidor DNS.
 
Requirements
------------

 * 

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.named
```


Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - named
...
```
Example 2 Container
----------------

```console
vagrant@localhost:~$ docker build .
vagrant@localhost:~$
vagrant@localhost:~$ docker run -dit --name my_server_bind9 wluisaraujo/bind9
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)