acme.db
=========

The Role install and secure MySQL on Ubuntu 20.0x and CentOS 8.
Then, configuring MySQL for rule of secure: change the root pass, remove remote connect 
as a root, remove others user, remove test db. Also role give the right permission on
folders and files, which must be protected. 
Create wordpress user and create table for wordpress.
Put the backup script and start cron shedule.

Requirements
------------

Ubuntu 20.04
CentOS 8

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
      become: yes
      roles:
         - { role: db }

License
-------

BSD

Author Information
------------------
Open source
