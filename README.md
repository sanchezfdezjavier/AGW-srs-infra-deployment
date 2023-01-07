# AGW-srs infra deployments

This repo contains infra as code templates for deploying AGW and SRS related infrastructure in AWS for testing purposes.

## Cloud Formation

You can use indistinctive both, `agw-srs-aws-scenario.cf.json` and `agw-srs-aws-scenario.cf.yaml`.

1. Go to CloudFormation service on the AWS management console.
2. Go to `Create Stack`, choose `Template is ready`.
3. `Upload a template file` and upload one of the two files.
4. Give the stack a name you want, and choose one of your KeyPairs for accessing the resources.

## Terraform

`agw-srs-aws-scenario.main.tf`
