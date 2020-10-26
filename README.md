Ansible MiniKube Installer
==========================

Prerequisite
------------
1. Oracle Virtual Box
2. Ansible 
3. Vagrant
4. ansible-galaxy collection install community.kubernetes

Steps
---------
1. Run vagrant up to create a new virtual machine
2. To install Minikube. Run ansible playbook: ansible-playbook -i inventory minikubeplaybook.yaml 

Author
------------
Adeel Shafqat
http://www.zaynsolutions.com
