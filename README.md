# update_reboot
This playbook works for on CentOS, Fedora, Ubuntu, Debian, Suse and Amazon-Linux.

This playbook will update package database and reboot the hosts.

****NOTE***
This playbook reboots hosts, any running service on the hosts will be interrupted by this reboot. 

Steps:

1. Updates yum package index
2. Refresh the cache
3. Reboots host
4. Wait for the system to boot up
