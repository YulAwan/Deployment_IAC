# Deployment_IAC
Distributed, Multi-Region Jenkins CI/CD Pipeline Deployment to AWS using Terraform and Ansible
Main Parts of the Project:
 - Plan the architecture od Deployment
 - Installation and config of Terraform, AWS CLI and Ansible
 - Set up AWS IAP Permissions for Terraform
 - Persisting Terraform State in S3 Backend
 - Setting up multiple AWS Providers in Terraform
 - NEtwork Setup, which includes setting up AWS infrastructure by creating necessary resources such as VPC, subnets, security groups, internet gateways and IAM roles using Terraform, deploying multi-region VPC peering
 - Deployment of App VM and Key Pairs for App Nodes
 - Deploying Jenkins Master and Worker Instances
 - Configuring Terraform Provisioners for Configuration Management via Ansible
 - Creating Ansible Playbooks for Jenkins MAster and Worker Instances
 - Creating an ALB and Routing Traffic to EC2 App Node
 - Setting up HTTPS and Route53 Record
 - Verifying IaC and Debugging
 
 
 
 
 Project was build on base of the course tutorial of ACG "Deploying to AWS with Terrafrom and Ansible" by Moosa Khalid
 
 
