SSH
=========

Configure SSH Server on Linux hosts

Requirements
------------

Must have SSH Port open, and ability to use SSH keys for authentication.

Role Variables
--------------

Group variables should be used per-environment/location

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible-ssh, SSH.port: 22 }

License
-------

University of Arizona

Author Information
------------------

CyVerse
=======
# ansible-ssh
Ansible tool to configure SSH on linux distributions
