acme.nginx1
=========

Install and configure Nginx with including some settings of PHP in templates.
Put test web-page and info.php to set that the php works correctly

Requirements
------------

CentOS 8
Ubuntu 20.04

Role Variables
--------------

All common vars discribed in vars/main.yml with comments
Vars for OS discribed in vars/Debian.yml or vars/RedHat.yml with comments too

Dependencies
------------
None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: nginx1 }

License
-------

BSD

Author Information
------------------

Open source
