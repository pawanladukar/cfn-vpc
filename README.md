# Repo: cfn-vpc
# AWS Cloudformation Stack for VPC Creation, templates for various scenarios
# - Replace ALL 'ProjectName' with your Project Name, or customize resources names as per requirements.
# - Create Stack in AWS Cloudformation by importing file or as s3 object.

# cfn_VPC_Template_1.yml
- Creates AWS Components like VPC, Public/Private Subnets, SG, Internet Gateway attached Public Route.
- Create EC2 Instance in PublicSubnet with PublicIP OR Create and attach EIP to connect your instance remotely using:wq
 Pubic IP.
