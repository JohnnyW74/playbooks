jw74.kvmHost
=========

Install all i need for working with kvm

Requirements
------------

Working Ubuntu and Ansible

Role Variables
--------------

tbd

Dependencies
------------

After executing this role for the first time you have to reboot, because rightsmanagement for virt-manager

Example Playbook
----------------

```
---
- hosts: local
  become: yes
  roles:
    - jw74.kvmHost
...
```
License
-------

GPLv3

Author Information
------------------

JohnnyW74
