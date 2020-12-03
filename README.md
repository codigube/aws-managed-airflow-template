# AWS Managed Airflow Template

CloudFormation template to deploy Amazon Managed Workflows for Apache Airflow(MWAA)

## Deploy

```bash
aws cloudformation deploy --template-file mwaa.yml --stack-name airflow-demo --capabilities CAPABILITY_NAMED_IAM
```
