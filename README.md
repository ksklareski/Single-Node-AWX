# Single Node AWX
Quick and dirty Ansible AWX setup using docker-compose on a single node which is intended for testing. 

This repo does not follow the current AWX best practices for installation.

## Note:
This playbook will only work against Ubuntu hosts. It also is not optimized whatsoever.

### Usage:
* Change inventory.yaml to suit your environment (or bring your own inventory file)
* Run "ansible-galaxy install -r requirements.yaml" to install required roles
* Run the playbook to install AWX