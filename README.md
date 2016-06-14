Network-hosts
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

License
-------

BSD
