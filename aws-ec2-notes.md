# AWS EC2 Notes

## What is EC2?
Amazon EC2 (Elastic Compute Cloud) is a service that provides virtual servers in AWS cloud.

## EC2 Components

### 1. AMI (Amazon Machine Image)
- Template used to launch an EC2 instance.
- Contains operating system and software configuration.

### 2. Instance Type
- Defines CPU, memory and performance of the server.
- Example: t2.micro (Free Tier eligible).

### 3. Key Pair
- Used for secure SSH connection to EC2 instance.
- Contains public key and private key (.pem file).

### 4. Security Group
- Acts as a virtual firewall.
- Common ports:
  - SSH - Port 22
  - HTTP - Port 80

### 5. EBS Volume
- Provides storage for EC2 instances.
- Data remains available even after stopping the instance.

## EC2 Troubleshooting
- Check instance status.
- Verify security group rules.
- Check Apache/web server status.
- Verify public IP address.
- Check application logs.

## Learning Outcome
Learned EC2 instance creation, security configuration and troubleshooting basics.
