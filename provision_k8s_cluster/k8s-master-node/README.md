k8s-master-node
=========

This role is used to configure the master node of k8s cluster.

Requirements
------------

No specific requirement.

Role Variables
--------------

NO variables.

Dependencies
------------

in inventory ip block name of master system must be 'master'. eg
```
[master]
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
