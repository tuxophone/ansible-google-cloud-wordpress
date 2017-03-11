# ansible-and-google-cloud

#Create virtual machine, domain and install wordpress:
ansible-playbook create.yml --extra-vars "domain=domain_name" --user=username --private-key=~/.ssh/ssh_private_key

#Destroy virtual machine and domain
ansible-playbook destroy.yml --extra-vars "domain=domain_name" --user=username --private-key=~/.ssh/ssh_private_key
