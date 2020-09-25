# How to Create an AWS Organization and Role Switching

## Introduction

- AWS Organizations enables you to centrally apply policy-based controls across multiple accounts in the AWS Cloud. 
- You can consoloidate all your AWS accounts into an organization, and arrange all AWS accounts into distinct organizational units. 

## Cloud Research
- You can add existing AWS accounts to your Org or create new accounts directly in the Org.
- IAM Roles can be used to allow IAM Users to access other accounts from one central place inside the Org. 
- Role Switch allows you to assume roles in other AWS accounts in your Organization so that you won't have to login to all of the different accounts. 

## Try yourself

# How to create an AWS Organization:

### Step 1 — In the AWS Organizations console, click on 'Create organization'

![Screenshot](https://user-images.githubusercontent.com/22378253/94221489-392ee180-feb9-11ea-8bc6-d04ddedbbcf3.png)

### Step 2 — Click on 'Add account'

![Screenshot](https://user-images.githubusercontent.com/22378253/94221551-55cb1980-feb9-11ea-8ac2-e7a8483f4c8a.png)

### Step 3 — 'Invite account' > enter email/account ID > write a short note > 'Invite'

![Screenshot](https://user-images.githubusercontent.com/22378253/94221581-667b8f80-feb9-11ea-8a20-3b33e1e55096.png)

# In the invited account: 

### Step 1 — In the invited account, check for the Invitation notification and Accept & Confirm the invite

![Screenshot](https://user-images.githubusercontent.com/22378253/94221696-a04c9600-feb9-11ea-9ecd-e645224139a8.png)

### Step 2 — In the IAM console, go to 'Roles' in the left navbar and click on 'Create Role'
- You're creating a Role which can be used by another AWS account (the master account)

![Screenshot](https://user-images.githubusercontent.com/22378253/94221973-32ed3500-feba-11ea-87b1-a4df902398ce.png)

### Step 3 — Select 'Another AWS account' > enter the Account ID of the master account

![Screenshot](https://user-images.githubusercontent.com/22378253/94222064-6d56d200-feba-11ea-914c-4f7e5b50aaf3.png)

### Step 4 — Attach the 'AdministratorAccess' policy 

![Screenshot](https://user-images.githubusercontent.com/22378253/94222137-8fe8eb00-feba-11ea-83c9-7d0066cb6384.png)

### Step 5 — Enter a Role name that you'll consistently use > description > 'Create role'

![Screenshot](https://user-images.githubusercontent.com/22378253/94222170-ab53f600-feba-11ea-8e1a-ae63979109e7.png)

# Role Switching:

### Step 1 — In the master account, click on the account dropdown menu & select 'Switch Roles'

![Screenshot](https://user-images.githubusercontent.com/22378253/94222332-11407d80-febb-11ea-9309-3e1184dcdd26.png)

### Step 2 — Click on 'Switch Role'

![Screenshot](https://user-images.githubusercontent.com/22378253/94222395-3cc36800-febb-11ea-9754-d6fb4644aa24.png)

### Step 3 — Enter the Account ID of the member account > enter the consistent Role Name > enter display name > click on 'Switch Role'

![Screenshot](https://user-images.githubusercontent.com/22378253/94222460-654b6200-febb-11ea-80af-8a18ec61ab20.png)


## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](link)
