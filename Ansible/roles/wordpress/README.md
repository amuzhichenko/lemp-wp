acme.wordpress
=========

The Role download and unpack the latest version of Wordpress on Ubuntu 20.0x and CentOS 8.
Then, configuring wp-config.php for rule of secure.

Requirements
------------

Ubuntu 20.04
CentOS 8

Role Variables
--------------

All common vars discribed in vars/main.yml with comments


Dependencies
------------
None

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
         - { role: wordpress }
License
-------

BSD

Author Information
------------------
Open source
