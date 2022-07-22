# Challenge1-CloudFormation
Challenge 1 - Create an EC2 instance in a given VPC

Write a CloudFormation script that will create the following two Resources: AWS::EC2::SecurityGroup and AWS::EC2::Instance.

You will have to write the suitable properties for each resource. Inside one of the properties' fields, you will have to specify the VPC and Subnet ID. Details of the resource to create are:

1-AWS::EC2::SecurityGroup
Creates a Security Group which only allows inbound access on TCP port 80 and also allows unrestricted outbound access.

2-AWS::EC2::Instance
Create a resource that deploys an EC2 Server and associate its network interface with the security group mentioned above. Use the following properties:

The instance type will be t3.micro.
You will need the AMI ID of the base Amazon Linux 2 AMI (HVM), SSD Volume Type, on top of which we’ll install our web server software.
