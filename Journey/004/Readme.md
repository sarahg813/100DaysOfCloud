# How to use IAM Access Keys with AWS CLI

## Introduction

You can authenticate the CLI with IAM Access Keys

## Cloud Research

An IAM user can create and delete Access Keys, and and make them inactive/active. <br />
When you create an Access Key, AWS will give you the credentials but will not store the Secret Access Key. <br />
You can't change the Access Key, you must delete it and make a new one. <br />
You can configure the AWS CLI and give it access to your accounts with your Access Key credentials.

## Try yourself

Steps to make your Access Key credentials and how to configure the AWS CLI

### Step 1 — In the IAM Management Console, click on 'Users' on the left navbar & then click 'Create access key'

![Screenshot](https://user-images.githubusercontent.com/22378253/92986027-d5062980-f485-11ea-8c2c-29babbf40eca.png)

### Step 2 — Keep note of the Access Key ID & the Secret Access Key. When you click the 'Close' button, you can't get the 'Secret access key' again

![Screenshot](https://user-images.githubusercontent.com/22378253/92986041-f23af800-f485-11ea-971f-38f688b8d887.png)

### Step 3 — Make sure you have the AWS CLI installed
In the terminal: <br />
aws configure --profile [profile name] <br />
Type in your AWS Access Key credentials <br />
Default region name: us-east-1 <br />
Default output format can be left blank

![Screenshot](https://user-images.githubusercontent.com/22378253/92986072-3af2b100-f486-11ea-9ef1-132243702fc3.png)


## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](link)
