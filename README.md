Tips for Ansible

1. How to change Ansible HOME

export ANSIBLE_HOME=/root/ANSIBLE
export ANSIBLE_CONFIG=/root/ANSIBLE/ansible.cfg

this will change Ansible home

2. How to Run playbook only on some host

ansible-playbook create_file_dir.yml --limit=muni1 whare muni1 is host name
