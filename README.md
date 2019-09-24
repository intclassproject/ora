"Hello World" simple Web application by using MongoDB database and Ansible Playbooks.

#Let’s run a playbook using a parallelism level of 10:
#ansible-playbook playbook.yml -f 10

#To see what hosts would be affected by a playbook before you run it, you can do this:
ansible-playbook playbook.yml --list-hosts
