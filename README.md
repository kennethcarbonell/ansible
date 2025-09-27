# ansible

Ansible personal lab experiment

This is the current command I am using to test ssh for ansible:

ansible -i ~/github/ansible/inv all -m ping

Current command to run playbooks:

ansible-playbook -i inv/inventory --ask-become-pass playbooks/playbook.yml

I have organized the inventory and playbooks in their respective directories.
