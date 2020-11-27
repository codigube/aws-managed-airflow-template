# AWS Managed Airflow Template

CloudFormation and Scripts to deploy Amazon Managed Workflows for Apache Airflow(MWAA)

NOTE: Up until now, CloudFormation resource is not available yet for MWAA.

## Deploy

### Deploy S3 buckets and Networking resources

```bash
aws cloudformation deploy --template-file mwaa.yml --stack-name airflow-demo
```

### Create environment from AWS Console

Create an environment by following the Console UI using resources created above.
