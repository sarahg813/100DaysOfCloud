# IAM Roles and AWS Organizations

## Cloud Research

IAM Roles
- An IAM Role is one type of identity which exists inside an AWS account.
- It's best to use them for an unknown number or multiple principals. 
  - such as multiple AWS Users inside the same AWS account or for applications or services inside/outside of your AWS account.
- Roles are for temporary use. 
  - A Role can represent a level of access inside an AWS account and can be used short term by other identities. 
- A Trust Policy can be attached to an IAM Role. It controls which idenities can assume that role. 
- A Permissions Policy can also be attached. Temporary Security Credentials are checked against the permissions policy.
- One common use is giving a Role to an AWS Service within the account such as AWS Lambda 
- Another use is if you have more than 5,000 staff members, you can use Single Sign On (SSO) and implement Identity Federation which allows an IAM Role inside your AWS account to be assumed by one of the external identities
- Another use is for an app that can scale to millions of users by using Web Identity Federation that uses IAM Roles. Customers can sign-in using a web identity and that'll allow them to assume an IAM Role. 

AWS Organizations
- It is a product that allows larger businesses to manage multiple AWS accounts
- With an AWS account, you can create an AWS Organization and that'll become the "master account." 
- The master account can invite other existing AWS accounts into the Org or it can create new AWS accounts and they "member accounts."
- There can only be one master account but zero or more member accounts. 
- The Organization Root is a container container member accounts/master accounts/other containers known as organizational units (OU).
- Consolidated Billing is one important feature of AWS Organizations.
  - Member accounts pass their billing to the master account 
  - The master account will get one monthly bill which covers the usage of the master account and all of the member accounts in the Org. 
  - With certain services, they get cheaper with the more usage you have and you can pay in advance in exchange for cheaper rates. 
- Service Control Policies (SCP) - lets you restrict what AWS accounts in an Org can do


## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](link)
