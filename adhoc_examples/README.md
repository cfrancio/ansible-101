# ad-hoc examples

### Topics Covered

* ansible installation methods
* create inventory file
* ad-hoc ansible
* command-line options
* using ansible.cfg


### Commands

* Install ansible with yum, but explain other methods (brew, pip, apt, etc)

	yum install ansible

* Create inventory file
	check inventory/hosts

* Run the following commands and experiment:

	ansible web -m ping -i inventory/hosts

or just the path:
	
	ansible web -m ping -i inventory/

* Specifying the inventory is annoying, so open up ansible.cfg 
Can be done on /etc/ansible/ansible.cfg

Uncomment the following entry for hostfile:
inventory      = /etc/ansible/hosts


* Check examples-101
