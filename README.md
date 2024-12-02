# Deploying-Three-Tier-Architecture
In this project, I will build a three-tier architecture in AWS. This consist of the presentation layer, the application layer, and the database layer. The architecture will be designed to be scalable, highly available, and support fault tolerance.

## •	Presentation Layer: 
A web server will serve the front end of the application using Amazon Elastic Load Balancing (ELB) to distribute traffic to multiple web servers running in Amazon EC2 Auto Scaling groups.

## •	Application Layer: 
The logic of the application will reside in an EC2 instance managed by an Auto Scaling group to handle dynamic content processing.

## •	Database Layer: 
A managed relational database, such as Amazon Aurora, will be used to store and manage application data.
This project will demonstrate how the three-tier work together to create a reliable, scalable and fault-tolerant three-tier application.  Security measures such as VPC, security groups, and IAM will be implemented to control access to resources.
