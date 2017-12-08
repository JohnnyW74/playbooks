Role jw74.synology
=========

my role for mounting my synology volumes on my notebook

Requirements
------------

synology exporting directores using nfs

Role Variables
--------------

|defined in|variablename|description|
|----------|------------|-----------|
|roles/jw74.synology/vars/main.yml|roleVarUser||
|roles/jw74.synology/vars/main.yml|roleVarUserGroup||
|roles/jw74.synology/vars/main.yml|roleVarSynologyIp||

Dependencies
------------

tbd

Example Playbook
----------------

```
- hosts: local
  become: yes
  roles:
    - jw74.synology
```

License
-------

GPLv3

Author Information
------------------

JohnnyW74
