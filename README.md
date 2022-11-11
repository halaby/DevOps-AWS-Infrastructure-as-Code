## Deploy a High-Availability Web App using CloudFormation


Create Stack
```bash
aws cloudformation create-stack --stack-name demo-project2 --template-body file://script/project-starter.yml  --parameters file://script/server-parameters.json --region=us-east-1 
```

Update Stack
```bash
aws cloudformation create-stack --stack-name demo-project2 --template-body file://script/project-starter.yml  --parameters file://script/server-parameters.json --region=us-east-1 
```

Delete Stack
```bash
aws cloudformation delete-stack --stack-name demo-project2
```
