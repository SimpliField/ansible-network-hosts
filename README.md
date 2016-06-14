Network-hosts [![Build Status](https://travis-ci.org/SimpliField/ansible-network-hosts.svg?branch=master)](https://travis-ci.org/SimpliField/ansible-network-hosts) [![Ansible Role](https://img.shields.io/ansible/role/10278.svg?maxAge=2592000)](https://galaxy.ansible.com/SimpliField/network-hosts/)
=========

Build /etc/hosts with all defined hostnames in inventory.
If ovh_vrack_ip is defined, it override ssh ip of the host.

Requirements
------------

Need ansible 2+

Role Variables
--------------

```yaml
```

Dependencies
------------

There is no dependency

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
   - { role: SimpliField.network-hosts }
```

License
-------

BSD
