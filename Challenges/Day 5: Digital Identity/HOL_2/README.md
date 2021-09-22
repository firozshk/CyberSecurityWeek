# Azure AD Privileged Identity Management and Azure AD Entitlement Management
# Challenge 

## Lab scenario

You have been asked to create a proof of concept that uses Azure Privileged Identity Management (PIM) to enable just-in-time administration and control the number of users who can perform privileged operations. Will also work on Azure Active Directory (Azure AD) entitlement management which is an identity governance feature that enable us to manage identity and access lifecycle, by automating access request workflows, access assignments, reviews, and expiration.

The specific requirements are:

- Create a permanent assignment of the aaduser2 Azure AD user to the Security Administrator role. 
- Configure the aaduser2 Azure AD user to be eligible for the Billing Administrator and Global Reader roles.
- Configure the Global Reader role activation to require an approval of the aaduser3 Azure AD user
- Configure an access packages with policies.
- Configure an access review of the Global Reader role and review auditing capabilities.

> For all the resources in this lab, we are using the **East US** region. Verify with your instructor this is the region to use for class. 

> Before you proceed, ensure that you have completed Lab 04: MFA, Conditional Access and AAD Identity Protection . 

## Lab objectives

In this lab, you will complete the following exercises:

- Exercise 1: Configure PIM users and roles.
- Exercise 2: Activate PIM roles with and without approval.
- Exercise 3: Create access package with a group and an application as resources. 
- Exercise 4: Create an Access Review and review PIM auditing features.

### Exercise 1 - Configure PIM users and roles

#### Estimated timing: 20 minutes

In this exercise, you will complete the following tasks:

- Task 1: Make a user eligible for a role.
- Task 2: Configure a role to require approval to activate and add an eligible member.
- Task 3: Give a user permanent assignment to a role. 


### Exercise 2 - Activate PIM roles with and without approval

#### Estimated timing: 20 minutes

In this exercise, you will complete the following tasks:

- Task 1: Activate a role that does not require approval. 
- Task 2: Activate a role that requires approval. 

### Exercise 3 - Create access package with a group and an application as resources. 

#### Estimated timing: 20 minutes

In this exercise, you will complete the following tasks:

- Task 1: Create a access package with two different policies.
- Task 2: The first policy enables a set of users in the directory to request access.
- Task 3: Access is defined with two different policies.  

### Exercise 4 - Create an Access Review and review PIM auditing features

#### Estimated timing: 20 minutes

In this exercise, you will complete the following tasks:

- Task 1: Configure security alerts for Azure AD directory roles in PIM
- Task 2: Review PIM alerts, summary information, and detailed audit information


