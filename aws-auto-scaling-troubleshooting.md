# AWS Auto Scaling Issue Troubleshooting

## Problem
Website is not opening after launching an EC2 instance with Load Balancer and Auto Scaling.

## Troubleshooting Steps

### 1. Check EC2 Instance
- Verify instance state is Running.
- 
- Check Status Checks (2/2 passed).
- Confirm Apache web server is running.

### 2. Check Security Group
- Allow HTTP traffic (Port 80).
- Allow SSH access (Port 22) for server connection.

### 3. Check Target Group
- Verify registered targets.
- Check target health status.
- Resolve unhealthy targets.

### 4. Check Application Load Balancer
- Verify Listener configuration.
- Confirm Listener forwards traffic to Target Group.
- Check ALB DNS name accessibility.

### 5. Check Auto Scaling Group
- Verify Minimum, Desired and Maximum capacity.
- Check new instances are launching properly.

## Learning Outcome
Learned how to troubleshoot AWS EC2, Load Balancer and Auto Scaling issues.
