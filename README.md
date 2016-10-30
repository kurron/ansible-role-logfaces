Role Name
=========

Installation of tools than any self-respecting JVM developer loves and needs.

Requirements
------------

TODO

Role Variables
--------------

* jvm_sdkman_install: true
* jvm_intellij_install: true
* jvm_intellij_version: 2016.2.4
* jvm_intellij_build: 162.2032.8
* jvm_intellij_share_jdk: true
* jvm_charles_install: true
* jvm_charles_version: 4.0.1

Dependencies
------------

* kurron.jdk

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.jvm-developer, jvm_charles_install: true }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
