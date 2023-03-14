jw74.ansibleHost
=========

This module is for initialising my ansible host.

Requirements
------------

For initial setup do the following things on a ubuntu-system >=18.04:

- sudo apt install python3-pip
- python3 -m pip install --upgrade pip
- pip3 install ansible
- ansible-playbook jw74.ansibleHost.yml -i inventory.yml

Role Variables
--------------

tbd

Dependencies
------------

tbd

Example Playbook
----------------

```
---
- hosts: local
  become: yes
  roles:
    - jw74.ansibleHost
...
```

License
-------

GPLv3

Author Information
------------------

JohnnyW74
