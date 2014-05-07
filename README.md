Awesome-Competence-System-Provisioning
======================================

Ansible powered provisioner for Ubuntu

Requirements
============
Ansible http://www.ansible.com
Ubuntu server
ssh key located in .ssh/id_dsa or equivalent

Usage
=====

Provisioning a Ubuntu server on EC2
-----------------------------------

To provison - Amazon AWS Access key and Secret must be entered into provision-ubuntu-yml. Remember to NOT CHECK IN these variables! 
ansible-playbook -i hosts provision-ubuntu.yml



Setting up ACS
--------------

ansible-playbook -i hosts site.yml
