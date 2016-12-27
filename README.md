Role Name
=========

Installation of client and server of the [logFaces](http://www.moonlit-software.com/) distributed logging aggregator.

Requirements
------------

TODO

Role Variables
--------------

TODO

Dependencies
------------

* kurron.jdk

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.logfaces, jvm_charles_install: true }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
