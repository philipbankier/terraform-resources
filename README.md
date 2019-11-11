# Terraform Resources

## AWS 

### Elastic Beanstalk
- Define an ElasticBeanstalk Application - https://github.com/cloudposse/terraform-aws-elastic-beanstalk-application
- Provision an ElasticBeanstalk Environment - https://github.com/cloudposse/terraform-aws-elastic-beanstalk-environment
- Provides an Elastic Beanstalk Application Version Resource - https://www.terraform.io/docs/providers/aws/r/elastic_beanstalk_application_version.html
### VPC
- Defines VPC with public/private subnets across multiple AZs with Internet Gateways - https://github.com/cloudposse/terraform-aws-vpc
- Enables flow logs for vpc and subnets - https://github.com/cloudposse/terraform-aws-cloudwatch-flow-logs

### RDS
- Official Module - https://github.com/terraform-aws-modules/terraform-aws-rds-aurora/blob/master/main.tf
- Cloudposse module - https://github.com/cloudposse/terraform-aws-rds-cluster/blob/master/main.tf

### Bastion host and access
- Stateless containerised sshd bastion service - https://github.com/joshuamkite/terraform-aws-ssh-bastion-service
- Bastion host: 
  - https://github.com/Guimove/terraform-aws-bastion
  - https://github.com/cloudposse/terraform-aws-ec2-bastion-server/blob/master/main.tf
## Terraform Best Practices

- Retrieve values from a store(SSM or Consul) over remote state - https://discuss.hashicorp.com/t/using-terraform-remote-state-over-common-data-filters/2376/2

## Terraform Tools
- Teraform configuration security check - https://github.com/liamg/tfsec
