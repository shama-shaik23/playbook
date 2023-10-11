Steps to install Ansible on AWS linux instance:
yum install python3 -y
yum install python3-pip
pip3 install ansible

This playbook is to install java and jenkins on local host.
Below is the command to run the playbook
ansible-playbook Installation.yml
=========================================

- To run from master host, define the list of the hosts in the inventory file
- in Installation.yml edit hosts
- below is the command to run
 ansible-playbook -i inventory Installation.yml
