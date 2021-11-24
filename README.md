# AWS Implementations

<div align='center'>
    <img src="Resources/aws implementation.gif " alt="drawing" width="600" />
</div>
<br>

##   

<div align='center'>
    <h2>Below you will read about some projects I have implemented using Amazon Web Services cloud platform</h3>
</div>

<!--
## Build a VPC and Launch a Web Server 

>Objectives:
> - Create a VPC
> - Create subnets.
> - Configure a security group.
> - Launch an EC2 instance into a VPC.

<br>
<div align='center'>
    <img src="Resources/52 VPC and Launch a Web Server.PNG " alt="drawing" width="500" />
</div>
<br>
-->

## Build A DB Server and Interact With that DB Using an App 

>Objectives:
> - Launch an Amazon RDS DB instance with high availability.
> - Configure the DB instance to permit connections from your web server.
> - Open a web application and interact with the database.

<br>
<div style="display: inline_block">
    <img src="Resources/160 uild Your Database Server.PNG " alt="drawing" width="400" />
    <img src="Resources/160 uild Your Database Server 2.PNG " alt="drawing" width="400" />
</div>
<br>

## Troubleshoot Creating an EC2 Instance Using the AWS CLI 

>Objectives:
> - **Launch an Amazon EC2 instance using the AWS CLI**
> - Troubleshoot AWS CLI commands and Amazon EC2 service settings

<br>
<div align='center'>
    <img src="Resources/173 Troubleshoot Creating an EC2.PNG " alt="drawing" width="500" />
</div>
<br>

## Using AWS Systems Manager

>Objectives:
> - Use AWS Systems Manager Inventory to verify configurations and permissions
> - Use AWS Systems Manager Run Command to run tasks on multiple servers
> - Use AWS Systems Manager Parameter Store to update application settings or configurations
> - Use AWS Systems Manager Session Manager to access the command line on an instance

<br>
<div style="display: inline_block">
    <img src="Resources/systemmanager.PNG " alt="drawing" width="400" />
    <img src="Resources/systemmanager2.PNG " alt="drawing" width="400" />
</div>
<br>

## Scale and Load Balance the Architecture

>Objectives:
> - Create an Amazon Machine Image (AMI) from a running instance.
> - Create a load balancer.
> - Create a launch template and an Auto Scaling group.
> - Automatically scale new instances within a private subnet
> - **Create Amazon CloudWatch alarms and monitor performance of the infrastructure.**

<br>
<div style="display: inline_block">
    <img src="Resources/174 Scale and Load Balance.PNG " alt="drawing" width="400" />
    <img src="Resources/174 Scale and Load Balance 2.PNG " alt="drawing" width="400" />
</div>
<br>

## Using Auto Scaling in AWS

>Objectives:
> - Create a new Amazon Machine Image (AMI) by using the Amazon **Command Line Interface (CLI)**.
> - Use Auto Scaling to scale up the number of servers available for a specific task when other servers are experiencing heavy load.
> - (Auto Scaling Launch Configuration, Auto Scaling Group, Auto Scaling Policies, ELB)

<br>
<div style="display: inline_block">
    <img src="Resources/175 auto scaling.PNG " alt="drawing" width="500" />
    <img src="Resources/175 load balancer.PNG " alt="drawing" width="350" />
</div>
<br>

## Route 53 Failover Routing
>Objectives:
> - Configure a Route 53 health check that sends emails when the health of an HTTP endpoint turns unhealthy.
> - Configure failover routing in Amazon Route 53.

<br>
<div align='center'>
    <img src="Resources/176.PNG " alt="drawing" width="500" />
</div>
<br>

## Working with AWS Lambda
The function steps shown in the diagram above are as follows:

1️⃣ An Amazon CloudWatch event triggers the salesAnalysisReport Lambda function at 8:00pm every day, Monday through Saturday. <br>
2️⃣ The salesAnalysisReport Lambda function invokes another Lambda function, salesAnalysisReportDataExtractor, to retrieve the report data. <br>
3️⃣ The salesAnalysisReportDataExtractor function runs an analytical query against the Café database (cafe_db). <br>
4️⃣ The query result is returned to the salesAnalysisReport function. <br>
5️⃣ The salesAnalysisReport function formats the report into a message and publishes it to the salesAnalysisReportTopic **Amazon Simple Notification Service (SNS) topic**. <br>
6️⃣ The salesAnalysisReportTopic sends the message by email.

>Objectives:
> - Recognize necessary IAM policy permissions to enable a Lambda function to other AWS resources.
> - Create a Lambda layer to satisfy an external library dependency.
> - Create a Lambda function.
> - Deploy and test a Lambda function that is triggered based on a schedule and that invokes another function.
> - Use CloudWatch logs to troubleshoot any issues running a Lambda function.
<br>
<div align='center'>
    <img src="Resources/178 lambda function.PNG " alt="drawing" width="500" />
</div>
<br>

## Migrate to Amazon RDS

>Objectives:
> - Create an Amazon RDS MariaDB instance **using the AWS CLI**.
> - Migrate data from a local MariaDB database to an Amazon RDS MariaDB database.
> - Monitor an Amazon RDS instance using Amazon **CloudWatch metrics**

<br>
<div style="display: inline_block">
    <img src="Resources/179 migrate rds 1.PNG " alt="drawing" width="400" />
    <img src="Resources/179 migrate rds 2.PNG " alt="drawing" width="400" />
</div>
<br>

## Troubleshoot a VP
>Tasks:
> - Create an Amazon Simple Storage Service (Amazon S3) bucket to hold the flow logs, and then enable VPC Flow Logs on VPC1.
> - Troubleshoot VPC1 network configurations. 
> - Download the flow logs to the CLI Host, and analyze the log entries.

<br>
<div align='center'>
    <img src="Resources/181 Troubleshoot a VPC.PNG " alt="drawing" width="400" />
</div>
<br>


