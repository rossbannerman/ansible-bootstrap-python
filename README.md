python
=========

Bootstrap Arch nodes with Python

Requirements
------------

N/A

Role Variables
--------------

This role currently only supports Arch: `ansible_os_family: Archlinux`

Dependencies
------------

N/A

Example Playbook
----------------
`gather_facts` must be set to `False`

```
- hosts: servers
  gather_facts: False
  roles:
    - role: python
```

License
-------

MIT / BSD
