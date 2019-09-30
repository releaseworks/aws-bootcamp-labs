# CloudFormation
The objective of this lab is to create an RDS instance, and connect to it.

## Readme
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-rds-database-instance.html
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-rds-dbsubnet-group.html
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-ec2-security-group.html

## To create
```
aws --region eu-west-2 cloudformation create-stack --stack-name my-stack --template-body file://stack.yaml
```

## To update
```
aws --region eu-west-2 cloudformation update-stack --stack-name my-stack --template-body file://stack.yaml
```