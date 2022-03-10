[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/timezone/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/timezone/tree/main)

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
