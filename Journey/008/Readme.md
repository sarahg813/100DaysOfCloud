# Create an Amazon EC2 Instance

## Introduction

 Amazon EC2 (Elastic Compute Cloud) provides scalable computing capacity in the AWS cloud. 

## Cloud Research

- It provides access to virtual machines known as instances
- An instance is an operating system configured in a certain way with a certain set of allocated resources
- It is a private service; uses VPC networking but you can configure it to have public access
- It is AZ resilient; the instance will fail if the AZ fails
- You can stop the instance from running and start it back up again but when you stop an instance, you will still be charged for storage
- You can terminate an instance to stop it from accruing charges but you can't start it back up again

## Try yourself

Steps to create an Amazon EC2 Instance:

### Step 1 — In the EC2 console, under 'Network & Security' on the left navbar then click on 'Key Pairs' & then 'Create key pair'

![Screenshot](https://user-images.githubusercontent.com/22378253/93546809-a24eac00-f931-11ea-9237-3971d015fe59.png)

### Step 2 — Create Key Pair
Give it a name. <br />
Choose 'pem' if you're using Mac OS or Linux. <br />
Choose 'ppk' if you're using the PuTTy terminal program. <br />
After you click 'Create key pair', you'll download the file of the keys.

![Screenshot](https://user-images.githubusercontent.com/22378253/93547228-88619900-f932-11ea-84ff-0a5c7a821f87.png)

### Step 3 — In the EC2 console, click on 'Launch Instance'

![Screenshot](https://user-images.githubusercontent.com/22378253/93547433-09209500-f933-11ea-8515-b9bd1e44163f.png)

### Step 4 — Select an AMI. 
Amazon Linux 2 AMI was chosen because it's free. 

![Screenshot](https://user-images.githubusercontent.com/22378253/93547511-30776200-f933-11ea-84d6-f8f11eff6a00.png)

### Step 5 — Choose an Instance Type. 
t2.micro was chosen because it's free.

![Screenshot](https://user-images.githubusercontent.com/22378253/93547653-877d3700-f933-11ea-9e47-8b14a01252e8.png)

### Step 6 — Configure Instance Details
Network: there's only one VPC and it's the default VPC <br />
Subnet: 'No preference' <br />
Auto-assign Public IP: 'Use subnet setting' is a default setting <br />

![Screenshot](https://user-images.githubusercontent.com/22378253/93547790-d88d2b00-f933-11ea-964c-9477e6cbd056.png)

### Step 7 — Add Storage
The defaults are provided by the AMI

![Screenshot](https://user-images.githubusercontent.com/22378253/93547847-ff4b6180-f933-11ea-973b-a081db3efb6a.png)

### Step 8 — Configure Security Group
For the source, you can choose 'My IP', so that only you will be able to connect to it. 

![Screenshot](https://user-images.githubusercontent.com/22378253/93547935-2efa6980-f934-11ea-9d4e-4b242bf7f10d.png)

### Step 9 — Review and Launch > Launch > Select an existing key pair or create a new key pair 

![Screenshot](https://user-images.githubusercontent.com/22378253/93548176-afb96580-f934-11ea-8688-855fbbda5436.png)

### Step 10 - Right click on the running instance and click 'Connect'
In your terminal, change directory to folder of where your saved key is. <br />
if you're using Mac or Linux, paste the command under #3 into the terminal and then paste in the command under Example 

![Screenshot](https://user-images.githubusercontent.com/22378253/93548409-28b8bd00-f935-11ea-85ca-edcd27152355.png)

### Step 11 - You can 'stop', 'start', or 'terminate' the instance.
Right clicking on the instance > Instance State > 'Start', 'Stop', or 'Terminate'

![Screenshot](https://user-images.githubusercontent.com/22378253/93548709-c7ddb480-f935-11ea-9183-449aabb5b637.png)

## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[https://twitter.com/sarahg813/status/1303903650079821825](https://twitter.com/sarahg813/status/1303903650079821825)
