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

1. Create a Vnet in a resource group if it doesn't exist. (Every other resources should consume same VNET)
2. Create public IP.
3. Create NSG with inbound and outbound rules.
4. Create subnet for Bastion. (The Ip ranges will be provided as per VNET created and developer inputs)
5. Create bastion and attach public Ip, NSG and Subnet and provide existing Vnet
7. Create Subnet for VM
8. Create VM and attach subnet and use existing Vnet from same resource group.

**Default Subnet name creation for bastion**

<img width="911" alt="image" src="https://github.com/Project-Learning-2024/CG-CE-Net/assets/77009306/3d412a35-4a9b-400b-967e-f3d645ee9f5e">

**Network Security Group Rules**

<img width="742" alt="image" src="https://github.com/Project-Learning-2024/CG-CE-Net/assets/77009306/4a6e0cab-b110-4303-845b-636275e86126">



   
