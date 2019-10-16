# Multi-Tenancy-Isoaltion-OpenStack
This is a Ansible Playbook for multi-tenancy isolation in Compute nodes and Block storage in OpenStack
this code is written for OpenStack that used LXC for running the services. 
For running the code:
Change the /etc/hosts and add the utility_container and its IP address in controller00
run the command below: ansible-playbook -i hosts playbook.yml
