# aws-lambda-deploy-demo

You will need to create an AWS CloudFormation role and add the AWSLambdaBasicExecutionRole policy to that role
```

aws iam create-role --role-name roleName 
```

Create S3 bucket
## Create S3 Bucket
```
aws s3 mb s3://aws-lambda-deploy-demo --region eu-west-1
```
