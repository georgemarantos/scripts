# scripts
Not sure where to put these yet however usefull commands to know for Ansible are:

ansible-playbook --syntax-check filename.yml 
ansible-playbook --check filename.yml

Line 4 will verify the syntax is correct
Line 5 will run the file without doing anything

ad-hoc command = ansible localhost -m ping