[![](https://github.com/ansible-roles-matsumura/vnc_server/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/vnc_server/actions?query=workflow%3Abuild)

Role Description
=========

Installs [VNC Server](https://tigervnc.org) for CentOS7.

Requirements
------------

EPEL installed before running this role.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - robertdebock.epel
    - vnc_server
```

License
-------

BSD
