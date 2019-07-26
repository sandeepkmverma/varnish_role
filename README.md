Varnish
============

An ansible role for the installation of Varnish with Apache on CentOS, Redhat, Debian and Amazon machine.

Requirements
------------

Python must be installed on remote server

Role Variables
--------------

```
# Defined in the variable section of the role

```

Dependencies
------------

None

Example Playbook
----------------

A playbook to use the role.

```
---
  - hosts: hostgroup/host
    become: true
    roles: 
      - varnish

```

Author Information
------------------

```
Name: Srishti Aggarwal
Email: srishti.aggarwal@opstree.com
```
