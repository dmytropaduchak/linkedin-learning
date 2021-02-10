## [AWS Essential Training for Developers](https://www.linkedin.com/learning/aws-essential-training-for-developers)

### AWS Essential Setup
------

Will you be charged for using AWS for the first time?

- [-] No. All services are free for the first year.
- [+] It depends. Some services offer a limited amount of free usage under the free tier.
- [-] Yes. All services in AWS always incur charges.
- [-] No. You are only charged after going live with your first project.

What is the most secure use case for your personal AWS access key? 

- [-] Share your access key with your team instead of sharing your AWS password.
- [-] Configure third-party API integrations with your access key.
- [+] Configure the AWS command line tools with your access key on your secured workstation.
- [-] Check the access key into your application's configuration file.

What is the best way to share your AWS account with your team?

- [-] Share the root user with everyone on your team.
- [-] Create an IAM user for each department and let them share accounts.
- [-] Use IAM to connect their amazon.com accounts to your AWS organization.
- [+] Create an IAM user for each team member.

What is something only the AWS root user can do?

- [+] Delete the AWS account.
- [-] Shut down all of the server instances.
- [-] Change the credit card on file.
- [-] Create a support ticket with AWS.

### On Premise to AWS
------

What is the difference between an availability zone and a region? 

- [-] An availability zone spreads across several regions for high availability applications.
- [-] An availability zone is a single server rack in the region's single data center.
- [+] A region is a geographical group of several availability zones that can consist of several individual data centers.
- [-] A region is a single data center and an availability zone is used for replication between regions.

In the shared responsibility model, which maintenance task will AWS perform on your EC2 instance?

- [+] Ensure that the physical server hardware is healthy.
- [-] Notify you of security vulnerabilities within your application.
- [-] Install operating system updates.
- [-] Schedule backups of your instance.

When you create a new server instance in AWS, what is happening behind the scenes?

- [+] AWS is creating a virtual machine (VM), which is a software abstraction that divides up the physical server's resources.
- [-] An order is placed for a new physical server to be racked within the AWS data center.
- [-] A Linux container is created with your selected operating system image.
- [-] You are leasing a physical server from AWS.

### IaaS Compute
------

What is the difference between horizontal and vertical scaling?

- [-] Vertical scaling stacks several virtual machines (VM) on top of a single physical server, whereas horizontal scaling spreads the VMs across several servers.
- [+] Vertical scaling is increasing the physical hardware to a single server. Horizontal scaling spreads traffic across several identical servers.
- [-] Vertical scaling uses several clones of a single virtual machine within a single region, whereas horizontal scaling spreads across regions.
- [-] Horizontal scaling allows a single virtual machine to combine the resources of several physical servers, whereas a vertical scaling uses a single server.

How does a security group protect your cloud infrastructure?

- [-] Traffic is allowed to flow between AWS services, but you must add rules to expose ports to the public internet.
- [+] All traffic is blocked by default and a security group rule allows external traffic.
- [-] All traffic is allowed by default, but you must add a security group rule for each port you want to block.
- [-] Security groups scan incoming traffic for suspicious requests.

When creating a new EC2 instance, how do you access it from the public internet?

- [+] Auto-assign a new public IP address.
- [-] Click the EC2 instance and under the Edit menu, select the "Make public" option.
- [-] Edit the security group and delete all of the existing rules.
- [-] Click the EC2 instance and in the details pane, click on the "Make public" link.

You will install a database engine on your EC2 instance that will continuously consume a large amount of CPU resources. What is the best EC2 instance type?

- [-] t3.xlarge
- [-] p3.2xlarge
- [-] r5.xlarge
- [+] m5.xlarge

If you switch computers and have lost your EC2 keypair, how do you connect to your EC2 existing instances?

- [-] You cannot recover an existing keypair. These instances will have to be terminated.
- [-] Contact AWS support and they can send you the keypair.
- [-] In the EC2 console, click Keypairs and click the download option.
- [+] Follow the instructions in the AWS documentation to generate a new keypair and recover your existing instances.

### IaaS Storage
------

What is a valid use case for a public S3 bucket?

- [-] storing database backups
- [-] sharing server log files within your team
- [+] serving web content with CloudFront
- [-] sharing reports with external vendors

Which S3 storage class is best for storing the only copy of your latest backups for your databases? 

- [-] S3 Glacier
- [-] S3 Databases
- [+] S3 Standard
- [-] S3 One Zone-IA

Why is using a IAM role better security than using access keys?

- [-] IAM roles can revoke permissions at any time, whereas an EC2 with access keys must be rebooted for permissions changes to take effect.
- [+] IAM roles grant permissions without leaving a key on the server that can be compromised.
- [-] IAM roles cannot grant dangerous permissions to an EC2 instance.
- [-] Access keys are shared among the team, but a role can only be applied to one EC2 instance at a time.

The AWS SDK requires that you always hard code it with an access key to access AWS services.

- [-] TRUE
- [+] FALSE

What CLI command will list all of the S3 buckets you have access to?

- [-] aws s3 list-buckets
- [+] aws s3 ls
- [-] aws s3 sync list
- [-] aws s3 cp

What is the order of the speeds of the AWS storage services by fastest (first in the list) to slowest (last in the list)?

- [-] EFS, S3, EBS
- [-] EBS, S3, EFS
- [-] S3, EBS, EFS
- [+] EBS, EFS, S3

If you are unable to mount an EFS volume, what is the most likely problem?

- [-] The EFS volume is not attached to the instance in the EC2 console.
- [-] The permissions on the EFS volume are incorrect.
- [+] A security group or firewall is blocking the network traffic to the EFS endpoint.
- [-] You need to change the storage class on the EFS volume.

What is the difference between an Amazon Machine Image (AMI) and an EBS snapshot?

- [-] There are no differences between an AMI and an EBS snapshot.
- [-] An EBS snapshot launches faster than an AMI.
- [-] An EBS snapshot is a full backup of your server's data, whereas an AMI only includes the base operating system.
- [+] AMIs include everything needed to relaunch the instance, whereas an EBS snapshot is only a backup of the data volume.

### IaaS Networking
------

If you want to use Route53, do you have to transfer your domain name to Route53?

- [-] Yes, you have to transfer your existing domain name into Route53.
- [-] Route53 will only work with domains that are purchased through Route53.
- [-] No, however you won't be able to use any of the extra routing features AWS included within Route53.
- [+] No, you only need to point your domain's DNS servers to the Route53 servers.

When choosing an Elastic Load Balancer (ELB), what is the difference between an Application Load Balancer (ALB) and a Network Load Balancer (NLB)?

- [-] There is no difference between an ALB or NLB.
- [-] An ALB is used for applications, whereas an NLB is used to bridge networks, such as your on-premise network.
- [+] An ALB is used for HTTP traffic, and an NLB is used for traffic that requires speed, like low-latency streaming services.
- [-] An ALB can be used for web applications, whereas an NLB is an older load balancer and shouldn't be used.

What is a trade off of placing your database server within a private subnet within your VPC?

- [+] You cannot access your database server with a database client tool unless you use a Client VPN connection.
- [-] The database will operate slower because of the secure tunnel.
- [-] There is no way to migrate an on-premise database into a private subnet.
- [-] There are no trade offs. This is the recommended best practice.

Can you lose the public IP address associated with your EC2 instance?

- [+] Yes, if you stop and start the instance.
- [-] Yes, if you reboot the instance.
- [-] Yes, when you edit the instance properties and release the IP address.
- [-] No, you will never lose the public IP address for your instance

What is the difference between an Internet gateway and a NAT gateway?

- [-] A NAT gateway can bridge 2 private subnets within a VPC, but an internet gateway can connect your private subnet to your on-premise data center.
- [-] An internet gateway will bridge 2 NAT gateways together.
- [+] A NAT gateway will not allow public originating internet traffic to pass to a server, but an Internet gateway will allow it.
- [-] An internet gateway provides internet access to servers within a VPC, but a NAT gateway only allows private traffic to flow within the VPC.

Why would you create a private subnet within a VPC?

- [-] to allow your EC2 instances to have private IP addresses that they can use to securely communicate with each other
- [+] to isolate database and file servers from public internet traffic
- [-] to create a secure tunnel between two availability zones
- [-] to create a secure tunnel between two regions

### Databases As a Service (DBaaS)
------

You have 10,000 Internet of Things devices that are sending in real-time telemetry on vehicle movement at 5-second intervals. What is the best service to capture this data?

- [-] SNS
- [-] MQ
- [-] SQS
- [+] Kinesis

If you need to store large streams of user activity data coming from a web and mobile application and generate aggregated reports on usage patterns, which database is the best choice?

- [-] Aurora
- [-] RDS for SQL Server
- [-] Neptune
- [+] Redshift

What in-memory caching server is NOT supported by ElastiCache?

- [-] Memcached
- [-] Redis 3
- [-] Redis 5
- [+] Elasticsearch

Which database is a NoSQL database type that can quickly store and retrieve key value pairs?

- [-] Neptune
- [-] RDS for MySQL
- [+] DynamoDB
- [-] Aurora

You are going to host an application that uses a MySQL database, but you do not want to manage scaling or database administration tasks. What is the best choice for hosting this database?

- [-] Launch an AMI image from the marketplace containing a pre-configured MySQL server.
- [-] RDS for MySQL
- [-] Redshift
- [+] Aurora

What is a valid use case for a queue or message broker that would sit in front of your relational database?

- [+] when you need to ingest a large stream of data
- [-] Message brokers don't work with relational databases.
- [-] when you need to temporarily store frequently accessed data returned from the database
- [-] when you need to transform data between a NoSQL database and a relational database

### Platform As a Service (PaaS)
------

What is usually the best service for implementing a multi-step workflow within AWS?

- [-] Batch
- [-] Workflows
- [+] Step Functions
- [-] SWF

You can create an entire web application using Lambda functions.

- [-] FALSE
- [+] TRUE

Which service can host a Docker container? 

- [-] Elastic Compute Cloud (EC2)
- [-] Elastic Beanstalk
- [+] All of these services can be used as a Docker host.
- [-] Elastic Container Service (ECS)

Which AWS service can host the web application server for a Wordpress site?

- [-] CloudFront
- [-] ElastiCache
- [-] S3
- [+] Elastic Beanstalk

### Software As a Service (SaaS)
------

To use IoT Core to track the state of your Internet of Things (IoT) appliances, you must select a device that is already certified for use with IoT Core.

- [-] TRUE
- [+] FALSE

What service can be used to transcode and splice together movie clips?

- [-] MediaChange
- [+] MediaConvert
- [-] Splice
- [-] Premiere

What service will identify the things it finds in an image?

- [-] Lex
- [+] Rekognition
- [-] Comprehend
- [-] Polly

What service can manage a REST API layer?

- [-] AppSync
- [+] API Gateway
- [-] GraphQL
- [-] Network Load Balancer (NLB)

What service can handle user authentication for your web and mobile applications?

- [-] Authenticator
- [-] Shield
- [-] IAM
- [+] Cognito

### DevOps with AWS
------

What is something that is difficult to monitor with CloudWatch?

- [+] internal application performance and response times
- [-] running container counts on ECS
- [-] memory usage on a Linux EC2 instance
- [-] status checks on an EC2 instance

Which tool is best at defining AWS services as code?

- [-] Chef
- [+] CloudFormation
- [-] Ansible
- [-] Puppet

What's the difference between continuous integration (CI) and continuous deployment (CD)?

- [-] There is no difference between CI and CD.
- [-] CD will automatically release your new code, while CI will monitor your new code in production and report on any errors.
- [-] If you already have a CI pipeline in place, then CD is already included in that process.
- [+] CI automatically builds your code and runs tests against it, while CD will automatically deploy working code.

What is DevOps? (find 3 correct items) 

A. View your infrastructure as code.
B. Monitor response times and application health.
C. IT people learn to code.
D. Operations and development teams share responsibilities.
E. A set of AWS automation tools. 

- [-] A,C,D
- [-] A,D,E
- [+] A,B,D
- [-] B,D,E

### Security on AWS
------

To comply with some of the auditing requirements of some compliance standards, what AWS tool can be enabled to maintain an audit log of access and changes to your AWS infrastructure?

- [-] GuardDuty
- [+] CloudTrail
- [-] AWS Audit and Compliance Tool
- [-] CloudWatch

An EC2 instance running a Wordpress site keeps getting hacked, even though you have restored the server several times and have patched Wordpress. What AWS service can help you detect the next time the server becomes compromised?

- [+] GuardDuty
- [-] Macie
- [-] Inspector
- [-] Shield

Web Application Firewall (WAF) deploys on top of what other AWS service?

- [-] VPC
- [+] Application Load Balancer (ALB)
- [-] CloudFormation
- [-] Shield
