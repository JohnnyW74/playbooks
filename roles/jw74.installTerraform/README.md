jw74.installTerraform
=========

installing terraform an terraform-provider-libvirt

read this for terraform-documentation: https://www.terraform.io/intro/getting-started/install.html
read this for terraform-provider-libvirt-documentation: https://github.com/dmacvicar/terraform-provider-libvirt


Requirements
------------

tbd

Role Variables
--------------

- roleVarTerraformDownload
- roleVarTerraformDownloadChecksum
- roleVarTerraformProviderLibvirtDownload

Dependencies
------------

tbd

Example Playbook
----------------

```
---
- hosts: local
  roles:
    - jw74.installTerraform
...
```

License
-------

GPLv3

Author Information
------------------

JohnnyW74