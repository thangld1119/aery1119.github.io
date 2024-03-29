---
title : "Set Up Website On EC2"
date :  "`r Sys.Date()`" 
weight : 7
chapter : false
pre : " <b> 7. </b> "
---


Create 1 more EC2 in the private subnet
First, create a keypair for a website host

![a](/images/7-SetUpWebsiteOnEC2/Pastedimage20240305152059.png)

Save it in the keypair folder of Bastion Host 

![a](/images/7-SetUpWebsiteOnEC2/Pastedimage20240305152420.png)

Next send the keypair to Bastion Host

![a](/images/7-SetUpWebsiteOnEC2/Pastedimage20240305152838.png)

Next create Web Instances

![a](/images/7-SetUpWebsiteOnEC2/Pastedimage20240305153529.png)

Set up Security Group for Web instances accessible only from Bastion Host

![a](/images/7-SetUpWebsiteOnEC2/Pastedimage20240305153814.png)

Next we use Bastion Host to access the Web Server

![a](/images/7-SetUpWebsiteOnEC2/Pastedimage20240305154211.png)

![a](/images/7-SetUpWebsiteOnEC2/Pastedimage20240305154340.png)

Then install the necessary libraries

![a](/images/7-SetUpWebsiteOnEC2/Pastedimage20240305154506.png)

Find the web resource here I download at the tooplate page 

![a](/images/7-SetUpWebsiteOnEC2/Pastedimage20240305154956.png)

Proceed to extract and coppy to html directory and restart httpd service

![a](/images/7-SetUpWebsiteOnEC2/Pastedimage20240305155424.png)

