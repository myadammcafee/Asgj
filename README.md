Tips for Ansible

1. How to change Ansible HOME

export ANSIBLE_HOME=/root/ANSIBLE
export ANSIBLE_CONFIG=/root/ANSIBLE/ansible.cfg

this will change Ansible home

2. How to Run playbook only on some host

ansible-playbook create_file_dir.yml --limit=muni1 whare muni1 is host name

PING all hosts 

ansible all -m ping

PING single host

ansible cldlvstgapp0152.corpzone.internalzone.com -i dev -m ping -u mlos

where hostname - cldlvstgapp0152.corpzone.internalzone.com
      dev - inverntory file-name
      mlos - username
