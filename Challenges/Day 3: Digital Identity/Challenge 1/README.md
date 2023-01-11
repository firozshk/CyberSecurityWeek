
# Azure AD Entitlement Management and Azure AD Privileged Identity Management  
# Challenge 

## Lab scenario

The specific requirements are:
- Create a new user in Azure with the naming guideline.
- Assign the below roles to the newly created user using Privileged Identity Management (PIM)
	* Global Reader
	* Security Reader
	* Assign Global Reader role as Eligible for a period of 30days & Security Reader role as permanent active.
- Configure an access packages with policies - Entitlement Management 


Expected Outcome
- Participant should login with the newly created user account and activate their Global Reader role, this will be validated by the approver.


## Naming Guidelines

While deploying the resources please follow the naming guidlines below. 
   
Please use respective username as a resource name for the Instructor to easily identity if the challenge was completed successfully. 
 
Example names: If an attendees name is `John Doe` where `John` being the First name and `Doe` being the last name.

      * Access Package Policy Name - `<Firstname-Lastname>-<Packagename>`  
	    Example - `john-doe-accesspack`
      * PIM Policy Name - - `<Firstname-Lastname>-<PIM>`  
	    Example - `john-doe-PIM`
 
