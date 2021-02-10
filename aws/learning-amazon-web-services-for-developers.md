## [Learning Amazon Web Services (AWS) for Developers](https://www.linkedin.com/learning/learning-amazon-web-services-aws-for-developers-2)

### Introduction
------

Which features and services does AWS have?

- [-] AWS is a cloud service provider that does storage for businesses who need to use offsite storage, due to file space limitation.
- [-] AWS serves as a hub for streaming media.
- [-] AWS is part of the Microsoft Azure and Google Cloud Platform and provides all the tools available in each platform.
- [+] AWS has, among other features: computing, management tools, mobile services, storage, database, and media services.

### AWS Console
------

Which storage item is commonly used for online storage?

- [-] Glacier
- [-] EFS
- [+] S3 or S3 buckets
- [-] Storage Gateway

### Security
------

In IAM, which areas need to be considered with restrictions and access?

- [+] Computing, Storage, Database, and App services
- [-] Websites, Storage, Security Groups, and Databases
- [-] Security Groups and URLs
- [-] URLs, Security Groups, and  Databases

What do Roles contain in AWS?

- [-] Roles are services for each AWS site.
- [-] AWS Roles are Admin, User, and Other.
- [+] Roles are collections of policies to which services are assigned.
- [-] Roles are used for levels of security.

When working with Cognito, what are Identity pools?

- [-] Identity pools link data from a user's local database to the AWS server.
- [-] Identity pools provide storage to AWS S3 buckets.
- [-] Identity pools are part of IAM.
- [+] Identity pools provide AWS credentials to grant your users access to other AWS services.

There are two ways to create a User Pool. What are they?

- [-] The two ways to create a User Pool are New and Existing.
- [+] The two ways to create a User Pool are Review defaults and Step through settings.
- [-] The two ways to create a User Pool are Wizard and Manually set User Pool.
- [-] The two ways to create a User Pool are Create a User Pool and Manually set a User Pool.

What is Anonymous Access?  

- [-] Anonymous Access is used with security to find out who has been on the AWS site.
- [-] Anonymous Access is used to verify security groups and roles.
- [-] Anonymous Access is a default user that AWS creates with any instance.
- [+] Anonymous Access creates Identity pools for you.

### Development
------

What is Lambda's functionality, and why is it used with AWS?

- [+] AWS Lambda is a computing service that lets you run code without provisioning or managing servers.
- [-] AWS Lambda is an IDE for developers. It is similar to Eclipse, Visual Studio, or Net Beans.
- [-] AWS Lambda is similar to DynamoDB, RDS, and Oracle.
- [-] AWS Lambda is used with security to find out who has been on the AWS site.

Can you use Oracle RDBMS with DynamoDB?

- [-] Yes, DynamoDB is part of the Oracle database, which is the preferred database storage in AWS.
- [-] Yes, Oracle is a non-relational database.
- [+] No, DynamoDB is for non-relational databases, and Oracle is a relational database.
- [-] No, DynamoDB does not work for all databases.

What is Simple Storage Service (S3)?

- [+] S3 is an online storage service.
- [-] S3 is a database for AWS.
- [-] S3 is a web service, similar to IIS and Tomcat.
- [-] S3 is used to backup personal data.

Which AWS IDE toolkit is beneficial for Developers to code, design, and run web applications with AWS?

- [-] Eclipse
- [+] AWS Cloud9
- [-] Visual Studio
- [-] Visual Studio Team Services (VSTS)

### Cross-Service Communication and Events
------

What is Simple Notification Service (SNS), and how is it different from SQS?

- [-] SNS is a subscriber and SQS is a publisher.
- [-] SNS stores messages in the queue, and SQS deletes messages off the queue.
- [+] SNS pushes its messages out to its subscribers, and SQS stores the messages until someone reads them and processes them off the queue.
- [-] SNS stores messages until someone reads them, and SQS pushes its messages out to its subscribers.

What is Simple Queue Service (SQS), and for what is it used?

- [+] SQS is useful for sending and receiving messages between apps.
- [-] SQS is useful for connecting to the Google Cloud Platform.
- [-] SQS is useful for managing S3 buckets.
- [-] SQS is useful for setting up security, users, roles, and groups.

Step functions are built on tasks and state machines.  What are state machines?

- [-] State machines are a concept used in designing computer programs or digital logic in AWS.
- [+] State machines are made up of states, their relationships, and the input and output defined by the Amazon States Language.
- [-] State machines are made up of states, behaviors, and the status of the states in AWS.
- [-] State machines are devices that contain a set of numbers, stable conditions, and present values.

### Deployment, Scalability, and Monitoring
------

Which kinds of alarms can be implemented into your AWS monitoring and management services with CloudWatch?

- [-] CloudWatch can implement alarms for power outages, security attacks, and vulnerabilities.
- [-] You can create alarms to monitor the users, security breaches, and sensitive data input/outputs from users.
- [-] With CloudWatch, you can create alarms for databases, security, and power outages.
- [+] You can create high-resolution alarms and automated actions. These alarms can monitor costs for your budget, metrics, events, and logs.

Elastic beanstalk creates a cloud formation stack. What does the cloud formation stack do?

- [-] The cloud formation stack is part of the AWS cloud platform.
- [+] The cloud formation stack helps you configure and maintain your system.
- [-] The cloud formation stack helps you set up VPN, TCP, and SSL protocols.
- [-] The cloud formation stack helps you manage the code repositories, similar to Subversion and Team Foundation (TFS).

CloudWatch alarms are part of Elastic Beanstalk, and there are two of them. What are the two alarms?

- [+] CloudWatch has two alarms to monitor loads, and they trigger when the alarms are too high or too low for the auto scaling group.
- [-] The two CloudWatch alarms are: timestamps and monitoring the storage usage.
- [-] The two CloudWatch alarms are: insufficient data and error messaging.
- [-] The two CloudWatch alarms are: specified metric and metric math expressions.

What are some benefits of CloudFront?

- [-] CloudFront is part of the CloudFormation stack.
- [-] CloudFront is a cloud-based shopping cart. This is AWS shopping cart software.
- [+] CloudFront is secure and quickly delivers data, video, applications, and APIs. This means it has shorter distances to deliver and higher performance.
- [-] CloudFront is a cloud network. It is wireless, not hardwired.

What is the AWS service ElastiCache?

- [-] ElastiCache is space in your virtual AWS instance that saves browser data from previously visited websites.
- [+] ElastiCache manages a distributed in-memory cache.
- [-] ElastiCache manages an experprise in-memory cache.
- [-] ElastiCache is levels of cache memory in your AWS service. It finds the data you need for its next operation.

### Conclusion
------

Why is it important to clean up your AWS?

- [-] Cleanup is the agile methodology for AWS. It involves the end of the sprint release.
- [+] If you do not clean up your AWS, you may be charged for services you are no longer using. Always check the billing services to see for what you are being billed.
- [-] Cleanup is part of the peer review for AWS platform security. It involves completing documentation on your AWS project, code reviews, and security for the AWS platform.
- [-] This cleanup is part of the maintenance in the last step of the AWS checklist.