# Ansible playbook for flink cluster Installation #
This is the flink role for flink installation. 

### This playbook is created with ansible 2.4 .It is tested on Ubuntu 16.04 LTS. ###

## Playbook requirements ##

* python-software-propertie
* Java jre 8

## Information ##
These ansible roles install and setup flink master-slave 
Here we have to specify varibles which are used for configuration of flink master and slave in vars folder.e.g, version, master_ip , slave_ip
##Steps to run playbook##
* Add hosts entry in /etc/hosts 
* Change variables as per requirement in tasks/vars folder
* At last simply run the play book on desired node.
