playbook_collection
=========

This is my playground with which I deploy my KVM instances on my laptop to play a little with docker
Read my blog-thoughts about the devops-movement: 
[https://www.tumblr.com/blog/johnnyw74](https://www.tumblr.com/blog/johnnyw74)

Requirements
------------

An installation auf Ubuntu 17.04(Zesty Zapus). It may work with an earlier version of Ubuntu, but it ist not tested.
An installation of ansible(http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-pip).

Installation
------------
To setup your own ansible host you have to run:
```
sudo ansible-playbook setup_ansibleHost.yml -i inventories/hosts.yml
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
