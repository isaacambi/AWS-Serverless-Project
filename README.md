# AWS-Serverless-Project

# Building an AWS Serverless Project


![image](aws.png)


1. Introduction to our project

In this project, we are going to build a simple serverless application using AWS services.
This tutorial is going to give you a introductory understanding to serverless architecture
and important AWS services. I hope you will enjoy it!

2. Services that we are going to use in this project

Amazon S3 (Simple Storage Service): serves as our application’s frontend hosting solution.
It stores and delivers static web content, such as HTML, CSS, JavaScript and images, ensuring
reliable and scalable delivery of these resources to users accessing the application via the internet.


AWS Lambda: as our backend’s serverless compute service. It executes code in response to various
events, such as HTTP requests, file uploads, and database updates, managing the application’s logic
and data processing without the need to manage traditional servers.

Amazon API Gateway: acts as a communication bridge between the frontend and backend of our application.
API Gateway handles incoming requests from clients, directing them to the appropriate backend resources, 
in our case, our Lambda function.

Amazon DynamoDB: serves as our application’s NoSQL database solution. It stores and manages structured
data with flexible schemas, enabling fast and scalable storage and retrieval of application data.

3. Setup

We have to create some files to our frontend. So here is the code for you:

index.html

