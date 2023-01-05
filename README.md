Playbooks for usage example:
=========

1) Edit hosts file.
2) Edit group_vars all.yml
3) Ping your hosts ```ansible-playbook -i hosts -e "servers=all" playbooks/ping.yml```
4) Install ipsec_checker ```ansible-playbook -i hosts -e "servers=all" roles/ansible_ipsec_checker/ansible_ipsec_checker.yml```

Vagrantfile:
=========
1) By default Vagrantfile create 2 VMs based on Centos 8 and Ubuntu 20.04

