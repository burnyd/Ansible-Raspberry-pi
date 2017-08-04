# Ansible-Raspberry-pi
![Alt text](Pis.jpg?raw=true "Pi")

This is a guide on how I deploy some of the Raspberry Pi's I have at home in a zero touch provisioning way.  Other than manually putting in the hostname and IP's of the loopback / ethernet0 addresses the rest is an easy configuration.  Part 1 will be simply getting the raspberry pi to boot from an SD card with the latest and greatest stable hypriotOS for the pi.  After in Part 2 I have a Kubernetes Ansible-Playbook that will run to make a minion/slave node join the Kubernetes master.


Step 1:
1.) Clone this repository #git clone https://github.com/burnyd/Ansible-Raspberry-pi.git 
2.) cd into the files directory and wget the latest and greatest hypriotOS image.
3.) Run the ./flash hypriotOS && ansible-playbook Ansible-Raspberry-pi/initial_build.yml # To kick off the build.

Click the video below to watch. 

[![Alt text](https://img.youtube.com/vi/8FNafYDGeOo/0.jpg)](https://www.youtube.com/watch?v=8FNafYDGeOo)

Part 2 joining the Pi coming soon. 
