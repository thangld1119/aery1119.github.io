---
title : "Set Up Application Loadbalance"
date :  "`r Sys.Date()`" 
weight : 8
chapter : false
pre : " <b> 8. </b> "
---


An Application Load Balancer is a load distribution service in AWS that is used to load balance traffic to applications operating across multiple servers or application processing resources. It helps to increase load capacity, improve performance and ensure application availability.

First step we create *target group* for loadbalance

![a](/images/8-SetUpApplicationLoadbalance/Pastedimage20240305155559.png)

Select the created VPC

![a](/images/8-SetUpApplicationLoadbalance/Pastedimage20240305155652.png)

I use the target group for the Web Host to open port 80 so that outside the Internet can access the website

![a](/images/8-SetUpApplicationLoadbalance/Pastedimage20240305155803.png)

Create a Security Group for Load Balance

![a](/images/8-SetUpApplicationLoadbalance/Pastedimage20240305160134.png)

Create Load Balance

![a](/images/8-SetUpApplicationLoadbalance/Pastedimage20240305160251.png)

![a](/images/8-SetUpApplicationLoadbalance/Pastedimage20240305160325.png)

Attention to select 2 public subnets in 2 zones

![a](/images/8-SetUpApplicationLoadbalance/Pastedimage20240305160445.png)

Security group

![](a../images/8-SetUpApplicationLoadbalance/Pastedimage20240305160626.png)

![](a../images/8-SetUpApplicationLoadbalance/Pastedimage20240305161025.png)

Done, now we coppy DNS and proceed to access the test site

![](a../images/8-SetUpApplicationLoadbalance/Pastedimage20240305161202.png)

Fruits

![](a../images/8-SetUpApplicationLoadbalance/Pastedimage20240305161247.png)
