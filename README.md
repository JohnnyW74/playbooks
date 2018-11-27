playbook_collection
=========

this are my playbooks i used to managed my things

Requirements
------------

An installation auf Ubuntu 18.04. It may work with an earlier version of Ubuntu, but it ist not tested.
An installation of ansible(http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-pip).

Installation
------------
To setup your own ansible host you have to run:
```
sudo apt install python3-pip
pip3 install ansible
ansible-playbook jw74.ansibleHost.yml -i inventories/hosts.yml -e 'ansible_python_interpreter=/usr/bin/python3'
```

Dependencies
------------

tbd

License
-------

GPLv3

Author Information
------------------

JohnnyW74
