# Terraform AWS Multi-Module Deployment
This Terraform script enables you to deploy multiple AWS modules using a single configuration.


## Prerequisites
Before using this script, make sure you have the following:
- [Terraform](https://www.terraform.io/downloads.html) installed on your local machine.
- AWS credentials properly configured to allow Terraform to access your AWS account.

## Configuration

To deploy multiple AWS modules, follow these steps:

**Clone this repository to your local machine:
  git clone https://github.com/vijaysexena/TF-Module.git**

Update the terraform.tfvars file with the required variable values for your deployment.

Modify the main.tf file to include the desired AWS modules and their respective configurations.


## Initialize the Terraform project:
terraform init


## Preview the changes that Terraform will make:
terraform plan


## Deploy the AWS modules:
terraform apply
Terraform will prompt for confirmation before making any changes. Enter yes to proceed.

## Modules
**This Terraform script supports the following AWS modules:**

**terraform-aws-ec2-module
terraform-aws-rds-module
terraform-aws-vpc-module
For more details on how to configure each module, refer to their respective documentation within their directories.**

## Clean Up
## To clean up and destroy the created resources, run the following command
terraform destroy


**Note: Be cautious while running this command, as it will destroy all the resources created by this Terraform configuration.**


## Contributing
If you find any issues with this Terraform configuration or have suggestions for improvements, please feel free to open an issue or submit a pull request.
