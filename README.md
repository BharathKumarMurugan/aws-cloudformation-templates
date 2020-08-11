# AWS CloudFormation templates

An example guide on AWS CloudFormation templates for various scenarios


Scenario | Template
-------- | --------
Create a VPC with IGW, Route Table, Public Subnet and Security Group | [Click Here](create-simple-vpc.yaml)
Create a VPC with IGW, Route Table, Public and Private Subnets, and NAT Gateway | [Click Here](create-vpc-with-subnet-nat.yaml)
Create a S3 bucket | [Click Here](create-s3-bucket.yaml)
Create a S3 bucket with CORS enabled and a policy attached | [Click Here](create-s3-with-policy.yaml)
Create an EC2 instance for webserver by importing values from another stack | [Click Here](create-webserver-instance.yaml)
Create an EC2 instance for webserver with region mapping | [Click Here](create-webserver-instance-2.yaml)
Create an IAM Role with Basic Lambda Execution Policy and AssumeRole attached | [Click Here](create-iam-role.yaml)
Create a sample AWS Lambda Function with a Role Attached | [Click Here](create-lambda-function.yaml)