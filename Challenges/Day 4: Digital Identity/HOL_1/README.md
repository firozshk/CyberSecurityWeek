
# Azure AD Entitlement Management and Azure AD Privileged Identity Management  
# Challenge 

## Lab scenario

You have been asked to create a proof of concept that uses Azure Active Directory (Azure AD) entitlement management which is an identity governance feature that enable us to manage identity and access lifecycle, by automating access request workflows, access assignments, reviews, and expiration. Will also work on Azure Privileged Identity Management (PIM) to enable just-in-time administration.

The specific requirements are:

- Configure an access packages with policies.
- Configure an access review of the Global Reader role and review auditing capabilities.
- Create an assignment on Azure AD user to the Security Administrator role. 
- Configure your respective user to be eligible for the Billing Administrator and Global Reader roles.


## Lab objectives

In this lab, you will complete the following exercises:

- Exercise 1: Create access package with a group and an application as resources. 
- Exercise 2: Create an Access Review and review PIM auditing features.
- Exercise 3: Configure PIM users and roles.
- Exercise 4: Activate PIM roles with and without approval.

### Exercise 1 - Create access package with a group and an application as resources. 

In this exercise, you will complete the following tasks:

- Task 1: Create a access package with two different policies.
- Task 2: The first policy enables a set of users in the directory to request access.
- Task 3: Access is defined with two different policies.  


### Exercise 2 - Create an Access Review and review PIM auditing features

In this exercise, you will complete the following tasks:

- Task 1: Configure security alerts for Azure AD directory roles in PIM
- Task 2: Review PIM alerts, summary information, and detailed audit information

### Exercise 3 - Configure PIM users and roles

In this exercise, you will complete the following tasks:

- Task 1: Make a your user eligible for a role.
- Task 2: Configure a role to require approval to activate and add an eligible member.
- Task 3: Give a user permanent assignment to a role. 

### Exercise 4 - Activate PIM roles with and without approval

In this exercise, you will complete the following tasks:

- Task 1: Activate a role that does not require approval.  
- Task 2: Activate a role that requires approval. 


## Naming Guidelines

While deploying the resources please follow the naming guidlines below. 
   
Please use respective username as a resource name for the Instructor to easily identity if the challenge was completed successfully. 
 
Example names: If an attendees name is `John Doe` where `John` being the First name and `Doe` being the last name.

      * Access Package Policy Name - `<Firstname-Lastname>-<Packagename>`  
	    Example - `john-doe-accesspack`
      * PIM Policy Name - - `<Firstname-Lastname>-<PIM>`  
	    Example - `john-doe-PIM`
 
