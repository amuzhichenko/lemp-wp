# ansible-lemp-wordpress

## Description of the task
Organise deploy LEMP stack + Wordpress to Ubuntu and CentOS machine. Front - nginx, back - Wordpress + PHP, DB for collection data from WP

## Check-points:
- Create role's for ansible
- Role's must validate via molecule
- Add generation tsl cert's for https connection to endpoint
- Without hardcoding. All settings must be in variables as can as possible
- Each role must has short readme for understanding purpose of it
- Deploy playbook on real machine and observe the correct setting's

## Result:
- Created role's 
- Current role's were deployed on VM's
