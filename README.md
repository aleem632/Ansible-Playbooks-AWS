# Ansible-Playbooks-AWS

![Ansible](https://github.com/aleem632/Ansible-Playbooks-AWS/blob/b5a588777db9e7bdc63d8e3c1008d1cc2e4ee4ba/Diagram/Ansible-AWS.png)



### PROBLEMS
- VPC consist of many moving parts
- subnets, NAT, Internet Gateways, Route Tables, NACL, Security Groups
- Bastion Host
- Human Error can lead to non functional or expesosed VPC
- Managing it manually Consumed all of time and effort 
### SOLUTION
- Configaration of management of VPC
- Automation Setup (No Human Error)
- Centralize Change management
- Version Control[IAAC]
### ANSIBLE SETUP ON AWS VPC 


![ANSIBLE SETUP](https://github.com/aleem632/Ansible-Playbooks-AWS/blob/57cd6b5df4d77664244df5e17ba73e1f74c55cf6/Diagram/Ansible-Setup.png)

### FLOW OF EXECUTION
- Login to aws 
- create ec2 instance to run ansible playbook
- Install Ansible
- Install boto
- Setup ec2 role for Ansible
- Create a project directory 
- Sample cloud task( with key pair)
- Create variable file for VPC & Bastion host
- Create VPC Setup Playbook
- Create Bastion Setup playbook
- Site.yml playbook to call both playbook at once




