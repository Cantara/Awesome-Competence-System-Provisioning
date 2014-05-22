Awesome-Competence-System-Provisioning
======================================

Ansible powered provisioner for Ubuntu

Requirements
============
Ansible http://www.ansible.com
Ubuntu server which requires Quantal for Libreoffice to be easily installed
ssh key located in .ssh/id_dsa or equivalent

Configuration
-------------
The following files must be added and set correctly
* ./hosts <- Addresses to servers to be used
* ./roles/django/vars/main.yml <- Secrets to DB, server address and so on


Setting up ACS
--------------

ansible-playbook provision-acs.yml
