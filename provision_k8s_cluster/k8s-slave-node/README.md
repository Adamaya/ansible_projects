k8s-slave-node
=========

This role is used to configure the slave node of k8s cluster.

Requirements
------------

No specific requirement.

Role Variables
--------------

NO variables.

Dependencies
------------

in inventory ip block name of slave system must be 'slave'. eg
```
[slave]
1.2.3.4
```
Example Playbook
----------------


    - hosts: servers
      roles:
      - role: k8s-master-node

License
-------

BSD

Author Information
------------------

[Adamaya Sharma](https://www.linkedin.com/in/adamaya-sharma/) 
