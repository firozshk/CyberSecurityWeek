# Microsoft Azure Cyber Security Workshop Instructions

Please follow these intrustions, to complete these challenges.

1. Sign-in to the Azure portal https://portal.azure.com/
> **NOTE**: Instructor would share the credentials while explaining the challenge. 

2. In the Azure portal, please use the Resource group "Hackathon" to deploy all the resources for completing the challenge. 
> For all the resources in this lab, we are using the **`East US`** region. Verify with your instructor this is the region to use for class. 

3. While deploying the resources please follow the naming guidlines below. 
    + All Azure resource types have a scope that defines the level that resource names must be unique. A resource must have a unique name within its scope. For example, a virtual network has a resource group scope, which means that there can be only one network named `vnet-prod-westus-001` 
    + Please use respective username as a resource name for the Instructor to easily identity if the challenge was completed successfully. 
    + Example names: If an attendees usename is `firozshk` 
      * Virtual machine format - `<username><vm><number>`  Virtual machine examples - `firozshkvm001`
      * Storage account format - - `<username><sa><number>`  Storage examples - `firozshksa001`
 
4. Please follow similar guidelines for creating Virtual Networks.`firozshk_Vnet01` with an address space of `10.0.0.0/24` will ve created as an example. Please use only respective Virtual Networks to deploy the resources. 
