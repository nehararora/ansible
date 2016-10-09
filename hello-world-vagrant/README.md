# Vagrant Hello World Ansible
Example of bringing up vagrant instance - Assumes vagrant is installed and setup already.

run:
```
ansible-playbook helloworld.yml --tags play1 
```
This will:
* Create a vagrant/ directory
* Add a Vagrantfile if one doesn't exist
* Initialize the vagrant machine
* Bring up Vagrant instance


run:
```
ansible-playbook helloworld.yml --tags play2
```
this will print out 
