[![](https://github.com/ansible-roles-mamono210/timezone/workflows/build/badge.svg)](https://github.com/ansible-roles-mamono210/timezone/actions?query=workflow%3Abuild)

Role Description
=========

Set system timezone for CentOS7/Stream8.

Requirements
------------

None

Role Variables
--------------

```YAML
---
# System timezone
system_timezone: 'America/New_York'
```

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
    - timezone
```

License
-------

BSD
