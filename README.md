# AWX-Ansible-Project

# When using Encrypted password with a vault-paasword file creaded
# The vault-password-file is created at the home directory
# Note: It has to be created outside the ansible config so that you will not accidentally check it into the git repo 

# Command for dry run for only rancher

# ansible-playbook -i inventory playbook.yml --vault-password-file ~/vault-password-file --tags rancher --check

# Command to run the playbook

# ansible-playbook -i inventory playbook.yml --vault-password-file ~/vault-password-file --tags rancher 
