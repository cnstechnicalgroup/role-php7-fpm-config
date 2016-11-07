Role: cns.php-fpm
========

This role applies custom configuration to stock php7-fpm install (Debian).

Requirements
------------

Nothing, it runs out of the box.

Role Variables
--------------

None.

Dependencies
------------

This package has no dependencies.

License
-------

GPLv2

Author Information
------------------

Sam Morrison

Examples
--------

```yaml
---
- name: common role test
  hosts: all
  roles:
    - cns.php7-fpm-config
```
