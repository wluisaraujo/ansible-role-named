[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-named-server.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-named-server)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Named Server](https://www.isc.org/downloads/bind/)

------------

Description
------------

 * Administrar um servidor DNS.
 
Requirements
------------

 * 


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
    - iac-ansible-named-server
...	
```

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
