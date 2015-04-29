ansible_salt-minion
===================

This playbook is used to quickly install the minion of a saltstack architecture.

## HOW it's working

This playbook uses two groups :
  - **salt_master** : define the saltstack master
  - **salt** : define minion hosts

## How to install

First, copy the directory **salt_minion** into your ansible roles directory.  
Next, create a playbook or include the code into a existing one (you can use playbook.example for an example of a working playbook for salt_minion)
Finally, associate hosts with **salt** group and the salt master host with **salt_master** group.
