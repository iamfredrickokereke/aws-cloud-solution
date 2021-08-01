# Cloud-solution-for-a-devops-team

![image](https://user-images.githubusercontent.com/38326256/127779110-1c21a07b-93b7-4861-9fe8-fea5784a1999.png)

This project implements a cloud web solution for a fictitious company with 2 products sample DevOps team using LAMP stack with remote Database and NFS servers.

Starting Off Your AWS Cloud Project
There are few requirements that must be met before you begin:

Properly configure your AWS account and Organization Unit Watch How To Do This Here

Create an AWS Master account. (Also known as Root Account)
Within the Root account, create a sub-account and name it DevOps. (You will need another email address to complete this)
Within the Root account, create an AWS Organization Unit (OU). Name it Dev. (We will launch Dev resources in there)
Move the DevOps account into the Dev OU.
Login to the newly created AWS account using the new email address.
Create a free domain name for your fictitious company at Freenom domain registrar here.

Create a hosted zone in AWS, and map it to your free domain from Freenom. Watch how to do that here

NOTE : As you proceed with configuration, ensure that all resources are appropriately tagged, for example:

Project: <Give your project a name>
Environment: <dev>
Automated: <No> (If you create a recource using an automation tool, it would be <Yes>)
