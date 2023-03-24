# ANSIBLE PLAYBOOK TO CREATE EC2

generate a key and add to the .ssh folder 
ssh-keygen -t rsa -b 4096 -f ~/.ssh/my_aws

Add you aws_secret key and access 
run " sudo ansible-playbook {playbook name}" 
