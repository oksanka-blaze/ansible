1) Install ansible to your system:

  http://docs.ansible.com/ansible/intro_installation.html

2) Copy deploy keys to `keys/` folder

3) To install all required software on server, run command:

  `ansible-playbook -i<server_address>, playbook.yml`
