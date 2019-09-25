# aws-wordpress

## Synopsis
There are three samples of template to create secure and scalable wordpress system.

1. First template creates the system with ALB + AutoScalingGroup + EC2 + RDS.  
2. Second template creates the system with ECS + EC2.
3. Third template creates the system with ECS + Fargate.

## How to use

### Template for traditional EC2 architecture
```
aws cloudformation create-stack --stack-name wordpress-ec2 --template-body file:///path/to/wordpress-ec2.yaml
```

## TODO
- [ ] Make password management secure
- [ ] Mount S3 to EC2 instances as NFS to make web instances stateless
- [ ] Create replica instance in RDS cluster
- [ ] Deployment
- [ ] ECS + EC2 template
- [ ] ECS + Fargate template