
# Azure Firewall
# Challenge
 
## Lab scenario

You have been asked to install Azure Firewall. This will help your organization control inbound and outbound network access which is an important part of an overall network security plan. Specifically, you would like to create and test the following infrastructure components:

- A custom route that ensures all outbound workload traffic from the VM must use the firewall.
- Firewall Application rules that only allow outbound traffic to www.bing.com. 

> For all the resources in this lab, we are using the **East US** region. 

## Lab objectives

In this lab, you will complete the following exercise:

### Exercise 1: Deploy and test an Azure Firewall

> For all the resources in this lab, we are using the **East (US)** region. 

In this exercise, you will complete the following tasks:

- Task 1: Deploy an Azure firewall.
- Task 2: Create a default route.
- Task 3: Configure an application rule. 
- Task 4: Test the firewall. 


**Please follow the below instructions**
1. Please use the same VM created during HOL_1
2. Create Azure Firewall 
- Firewall Name - **Please follow naming guidelines**
- Firewall Tier - **Standard** 
- Firewall Management - **Firewall Policy to Manage this Firewall**
- Firewall Policy - **Create New** - **Please follow naming guidelines**
- Virtual Network - **Please select the VNet previously created for VM**
- Subnet - **New Subnet** 
- Public IP - **Add New**


**Please have the remaining setting as deafult**

### Minimum Expected Outcome 

1. VM traffic should be via Azure Firewall
2. VM should only access www.bing.com 
3. All the access to other websites should be blocked
