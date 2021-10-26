# Azure Sentinel
# Challenge

## Lab scenario 

You have been asked to create a proof of concept of Azure Sentinel-based threat detection and response. Specifically, you want to:

- Start collecting data from Azure Activity
- Create a workbook for Azure Activity 
- Add built in and custom alerts 

> For all the resources in this lab, we are using the **East US** region. 

## Lab objectives

In this lab, you will complete the following exercises

### Exercise 1: Implement Azure Sentinel

In this exercise, you will complete the following tasks:

Task 1: On-board Azure Sentinel

Task 2: Connect Azure Activity to Sentinel

Task 3: Create a workbook for Azure Activity 

Task 4: Create a custom analytic rule that uses the Azure Activity data connector. 



- Task 1: Please follow the below instructions to create a new log analytics workspace. 

      **DO NOT USE ANY EXISTING LOG ANALYTICS WORKSPACE**

   - Workspace Name - Please follow naming guidelines


- Task 2: Please follow the below instructions to connect Azure activity via connector (approx-15-20mins to see the results)
  - Please select the subscription and the respective resource group.
  - Select the log analytics workspace created during Task 1

- Task 3: Create a workbook for Azure Activity as the Azure activity connector would be connected in the backend.

- Task 4: Create a custom analytic rule 

## Naming Guidelines

While deploying the resources please follow the naming guidlines below. 
   
Please use respective username as a resource name for the Instructor to easily identity if the challenge was completed successfully. 
 
Example names: If an attendees name is `John Doe` where `John` being the First name and `Doe` being the last name.

      * Virtual machine format - `<Firstname-Lastname>-<vm>-<number>`  
	    Example - `john-doe-vm-01`
      * Log Analytics Workspace format - - `<Firstname-Lastname>-<law>-<number>`  
	    Example - `john-doe-law-01`
 
## Expected Outcome
1. Azure Activity should be successfully conncted to Azure Sentinel
2. The custom analytic rule created should return valid output 
