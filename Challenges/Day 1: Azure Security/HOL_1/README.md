
# Azure Security Center
# Challenge

## Lab scenario 

You have been asked to create a proof of concept of Security Center-based environment. Specifically, you want to:

- Create a VM (Virtual Machine) and onboard to Azure Defender under Azure Security Center.
- Review Security Center recommendations for the virtual machine.
- Implement recommendations for VM and enable Just in time( JIT) VM access. 
- Review how the Secure Score can be used to determine progress toward creating a more secure infrastructure.

> For all the resources in this lab, please use the **East US** region only.  

## Lab objectives

In this lab, you will complete the following exercise:

### Exercise : Monitoring Virtual Machine with Azure Security Center/Azure Defender

In this exercise, you will complete the following tasks:

- Task 1: Create a Windows Virtual Machine
- Task 2: Enable Azure Defender on VM
- Task 3: Review the Security Center recommendations
- Task 4: Implement the Security Center recommendation and enable Just in time VM Access

**Please follow the below instructions**
1. Create new Vitual Machine
- Virtual Machine Name - **Please follow naming guidelines**
- Availability Options - **No** 
- Image - **Windows 2019 Server**
- Size - **Standard_DS1_v2**
- Disk - **Standard HDD**
- Virtual Network - **Create New and follow naming guidelines**
- Subnet - **Default** 
- Public IP - **No**

**Please have the remaining settings as deafult**

### Minimum Expected Outcome 

1. VM should be monitored by Azure Defender 
2. Just in time access should  be enabled on the VM
3. Vulnerability assessment should be installed
