ec2-instance
=========

Launches 3 ec2 instance of same type and updates the the inventory dynamically

Requirements
------------

IAM role must be created because their credential gonna used to connect to user's account.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. region, subnet_id, instance_type, key, sg.

Dependencies
------------

No dependency.

Example Playbook
----------------


    - hosts: servers
      roles:
      - role: ec2-instance

License
-------

BSD

Author Information
------------------

[Adamaya Sharma](https://www.linkedin.com/in/adamaya-sharma/)
