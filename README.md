# LITA-AWS_EC2-PROJECT
This project document the process of launching EC2 instance and deploying Apache web server on it
### launched an EC2 instance 
EC2 Instances was launched to Host the Web Application, The instance has an appropriate Amazon Machine Image (AMI) for your web Application and instance type.
Below is the Image of my EC2 instance details that was launched
![EC2 instance launched](/ec2_instance1.PNG)
![EC2 instance launched](/ec2_instance2.PNG)
#### Successfully launched EC2 instance
![EC2 instance launched successfully](/ec2_instance.PNG)
#### AMI Used
![AMI](/AMI.PNG)
#### Instance type used
![instance type](/instance_type.PNG)
#### Keypair Creation
I Created a Keypair, for my EC2 instance, Below is the image of the keypair details created
![Keypair](/key_pair.PNG)

### Subnet Creation
I Created 2 Subnets, Public and Private Subnet, Below are Images of Subnet Created
#### Public Subnet
![Public Subnet](/public_subnet.PNG)
#### Private Subnet
![Private Subnet](/private_subnet.PNG)

### VPC Creation
I created a VPC to house my resources into the AWS environment. The VPC has a CIDR of 10.0.0.0/16
Below is the image of my vpc details
![VPC](/vpc.PNG)

### Security Group Creation
I Created Security Group with inbound rule to all SSH and HTTP traffic, Outbound rule to allow all traffic
![Security Group](/Security_group.PNG)
#### Inbound Rule
![Inbound rule](/inbound_rule.PNG)
#### Outbound Rule
![Outbound rule](/outbound_rule.PNG)

### Install and configure a web server Apache 
I Installed and configure Apache web server on EC2 instance using gitbash
![Test page](/test_page.PNG)