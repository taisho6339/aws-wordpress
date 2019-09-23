# aws-wordpress

## Synopsis
This repository has three templates to create scalable wordpress system.

1. First template creates the system using ALB + AutoScalingGroup + EC2 + RDS.  
2. Second template creates the system using ECS + EC2.
3. Third template creates the system using ECS + Fargate.

## How to use

### Template for traditional EC2 architecture
```
aws cloudformation create-stack --stack-name wordpress-ec2 --template-body file:///path/to/wordpress-ec2.yaml
```
