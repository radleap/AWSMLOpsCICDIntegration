# README.md
Project related to integrating CICD Pipeline for ML Ops using AWS IAC. 

- infra: contains CloudFormation template **pipeline.yml**, that you will use to create the CI/CD pipeline
- source: contains the code that will be used to train and test the model
- lambda: contains a Lambda function that can query the endpoint of the model

# Resources
- https://workshops.aws/categories/MLOps
- https://catalog.us-east-1.prod.workshops.aws/workshops/50716cb8-6a42-427f-9eeb-0465dea6e95b/en-US/cicd
- https://docs.aws.amazon.com/sagemaker/latest/dg/onboard-quick-start.html
- https://www.youtube.com/watch?v=Qv_Tr_BCFCQ
- https://docs.aws.amazon.com/sagemaker/

### Useful template code:
- https://docs.aws.amazon.com/code-samples/latest/catalog/cloudformation-codepipeline-template-codepipeline-github-events-yaml.yml.html