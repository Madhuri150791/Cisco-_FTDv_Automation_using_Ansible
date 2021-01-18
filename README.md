# Cisco-_FTDv_Automation_using_Ansible
Automating Cisco NGFW solution using Rest API via Ansible


 Problem Statement:
 
 Manage ISE day to day Operation like adding Network Device, Internal Users etc using a standard Automation Language which can be spanned to other Network           Device.
 
 Solution:
 
 Customer Network are now moving to utilise Automation capabilities available within Network Devices/Products to avail ease of operation and less human               error. Keeping the same in mind, Ansible is one such automation lanaguage whih can be leveraged as central methodology to managae all Network Device present         in the network. The same can be extended to Cisco FTD which is Next Gen Firewall used in the Enterprise/DC/SP Network.
 
 
 This script explores the option to use REST API using Ansible.
 
 
 Benefit :
 
 No need invest on learning curve for new scripting language like Python. Ansible can be used to manage CLI as well as REST API based Devices.
 
 Usage:
 
 Clone the repo.
 
 git clone https://github.com/Madhuri150791/Cisco-_FTDv_Automation_using_Ansible.git
 
 1. Edit FTD_Inventory.txt
 
 Put your FTDv Device under the group mylabserver.
 
 2. Run the playbook.
 
 ansible-playbook -i FTD-inventory.txt FTD-playbook.yml
 
 Note: PLease make sure you have ansible installed in the local machine from where you are running the ansible.
 
 For more clarification on the code please visit https://www.linkedin.com/pulse/setting-up-ansible-cisco-ise-madhuri-dewangan/

