# AWS Managed Airflow Template

CloudFormation template to deploy Amazon Managed Workflows for Apache Airflow(MWAA)

## Deploy stack

```bash
aws cloudformation deploy --template-file mwaa.yml --stack-name airflow-demo --capabilities CAPABILITY_NAMED_IAM
```

## Destroy stack

```bash
aws cloudformation delete-stack --stack-name airflow-demo
```
