**TASK : TO HAVE SECURE CONNECTION TO VM's USING BASTION**

As it needs to be secured within an environment, we must bring them into an Virtual network allowing specifics to access
the VM's through bastion. So every resources must be setup into Virtual network.

**Dependent Resources :**
1. VNET
2. BASTION
3. PUBLIC IP
4. SUBNET
5. NSG

**Creation of resources and dependencies**

1. Create a Vnet in a resource group it it doesn't exit
2. Create public IP 
3. Create NSG with inbound and outbound rules.
4. Create subnet for Bastion.
5. Create bastion and attach public Ip, NSG and Subnet and provide existing Vnet
7. Create Subnet for VM
8. Create VM and attach subnet and use existing Vnet from same resource group.


   
