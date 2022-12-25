acme.php
=========

The role installing and start PHP with dependencies for using with NGINX, MySQL

Requirements
------------
Ubuntu 20.04
CentOS 8

Role Variables
--------------
php_packages - packages of PHP with dependencies for needed OS

Dependencies
------------
None
Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: php }

License
-------

Open source

Author Information
------------------
