# Vagrant Hello World Ansible
Assumes vagrant is installed and setup locally.

run:
```
ansible-playbook helloworld.yml
```
This will:
* Create a vagrant/ directory
* Add a Vagrantfile if one doesn't exist
* Initialize the vagrant machine
* Bring up Vagrant instance
