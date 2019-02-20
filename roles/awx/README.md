Ansible-AWX
=========

An ansible-role for installing MrMEEE's RPMified version AWX.
This is a very work-in-progress project and so far it will only install AWX.

Requirements
------------

RHEL or CentOS (and derivatives, I suppose)

Role Variables
--------------

The name of the host to install to, is found in tasks/install-awx.yml, and can be freely edited to your liking-

Dependencies
------------
No dependencies.

Example Playbook
----------------

Download the role to you role-directory (the tasks-directory can be put where ever you feel like it) and run it:

ansible-playbook tasks/install-awx.yml

License
-------

BSD

Author Information
------------------
-