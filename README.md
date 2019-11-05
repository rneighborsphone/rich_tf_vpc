# rich_tf_vpc
Frist terraform module  used to create  a AWS VPC

# AWS VPC module for Terraform 
A lightweight VPC module for Terraform. 
## Usage
module "vpc_basic" 
{ source = "github.com/rneighborsphone/tf_rich_vpc"
name = "vpc_name" 
cidr = "10.0.0.0/ 16" 
public_subnet = "10.0.1.0/ 24" 
} 
# Added this test line


See ` interface.tf ` for additional configurable variables. ## License MIT

