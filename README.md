# Ansible-Raspberry-pi
This is a guide on how I deploy some of the Raspberry Pi's I have at home in a zero touch provisioning way.  Other than manually putting in the hostname and IP's of the loopback / ethernet0 addresses the rest is an easy configuration.  Part 1 will be simply getting the raspberry pi to boot from an SD card with the latest and greatest stable hypriotOS for the pi.  After in Part 2 I have a Kubernetes Ansible-Playbook that will run to make a minion/slave node join the Kubernetes master.


