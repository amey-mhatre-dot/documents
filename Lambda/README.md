# Lamda-demo

# Case Study
It helps to create a backend API system for employee data management. The below flows are covered - 
* New Employee record insertion.
* Update existing employee record based on employeeId
* Get specific employee record based on employeeId
* Delete employee record based on employeeId
* Fetch all the employee recordA monitoring API to check the health
* Use DynamoDB and its table items should be - employeeId (primary-key), empname, studio, projectname, location. 

For this case study, you will use below AWS services - 
* AWS API Gateway - You will create 6 REST API’s.
* AWS Lambda - One Lambda function supporting 6 API’s
* IAM roles - For access permission in between API Gateway, DynamoDB and Lambda.
* DynamoDB - You need to maintain all the employee data in DynamoDB table
* Cloudwatch - The API request & response will be tracked using Cloudwatch

For Lambda function source code refer index.js
