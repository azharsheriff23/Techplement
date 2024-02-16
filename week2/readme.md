Techplement -week2 Project
Team : Cloud03
Team Member : Azhar Sheriff I, Shubham Muge

Project Details :  Deploying Web Application on EC2.
Description: Deploy a web application on an Amazon EC2 instance using an appropriate programming language and web framework. Implementation: Set up an EC2 instance, install necessary software, configure security groups, and deploy the web application code. Use Elastic IP for a static IP address and Elastic Load Balancer for load balancing if required.

Primary Goal: Based on the Project Description we have decided to maintain the architecture as highly available. 
We have decided to Deploy a Shopping application

Services Used:

Virtual Private Cloud:
The VPC places a role to maintain the services which are associated to that vpc should be highly secure within the region. 
The Netmask of the vpc is 10.0.0.0/25
Two Availability zones and two subnets, each Az’s have one subnet
The subnet mask are 10.0.0.0/26, 10.0.0.64/26
We have configured the Internet gateway to main route table to publically accessable.

EC2 Compute:
Here we are using compute power service as elastic cloud compute and attaching it to the custom vpc which we have created.
