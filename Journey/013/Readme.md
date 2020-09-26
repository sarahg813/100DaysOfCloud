# Service Control Policies

## Introduction

Service Control Policies (SCPs) are a type of Organization policy that you can use to manage permissions in your Org. They help you to ensure your accounts stay within your organization's access control guidelines.


## Cloud Research

- SCP is a policy document (JSON) and they can be attached to the Org as a whole by attaching them to the root container.
- They can be attached to one or more Organizational Unit (OU) or they can be attached to one or more AWS account directly. 
- If an SCP is attached to the Org then they affect all accounts inside the Org.
- If they're attached to an OU then they impact all accounts in all OUs below that OU.
- The master account is never affected by any SCPs. 
- SCPs do not grant any permissions.
- SCPs are just boundaries that control what is allowed and what isn't allowed.
- You can create an 'allow list' which blocks services by default but allow certain services.
- You can create a 'deny list' which allows services by default but deny certain services. 
- When you enable SCPs on your Org, AWS applies a default policy called 'FullAWSAccess' to the Org and all OUs in that Org. 


## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](link)
