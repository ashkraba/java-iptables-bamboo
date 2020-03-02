# Bamboo CI/CD installation

This ansible roles help you create CI/CD server with Atlassian Bamboo:

  - Disable Selinux and Firewalld
  - Install iptables and configure rules for it
  - Create user for bamboo
  - Install bamboo

# IMPORTANT! Before using this roles:

  - change accepted ports for iptables (because this roles clear all your rules)
  - change hosts in hosts.txt file according to your environment
  - this roles only install bamboo and you should activate it manually with your private activation key

You can also:
  - change a lot of default variables in every appropriate file for every role
  - use only the roles you need, roles are independent

# Notes:
All this roles was tested on default VirtualBox virtual machines with CentOS. If you found any mistakes please let me know. I hope this roles help you and save some working time.
