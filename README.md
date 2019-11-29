Ansible_chef_bootstrap
----------------------
This playbook runs the Knife bootstrap command on a chef workstation.
A bootstrap installs Chef Infra Client on a target system so that it can run as a client and communicate with Chef Infra Server.


Follow the below steps to execute the Playbook on Ansible Tower
----------------------

(1) Click [Here](https://tower.its.hpecorp.net/#/login) to login to Tower.


(2) Go to the templates section and find "Ansible_Chef_node_bootstrap" and then hit " start job using this template" button.

![](https://github.hpe.com/HC-Automation/Ansible_chef_bootstrap/blob/master/Images/template_start.png)


(3) you will be prompted to enter the hostnames and the common username that exist for all hosts which you want to bootstrap. ( please make sure the YAML syntax is followed while entering the hostnames)

![](https://github.hpe.com/HC-Automation/Ansible_chef_bootstrap/blob/master/Images/hostname_username.png)



(4) Next, you will be prompted to enter the password that will be used on all hostnames. So enter the password and hit next.

![](https://github.hpe.com/HC-Automation/Ansible_chef_bootstrap/blob/master/Images/psswd.png)

(5) Verify the entered values and then hit 'Launch'

![](https://github.hpe.com/HC-Automation/Ansible_chef_bootstrap/blob/master/Images/launch.png)


(6) Tower will start executing the playbook. Wait for the job to get finished

