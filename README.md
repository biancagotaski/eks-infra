# Infrastructure with Kubernetes on AWS using Terraform

This source code can be used as a Terraform template for a basic setup of a Kubernetes cluster infrastructure on AWS, which contains:

- A VPC with private and public subnets 
- 2 groups of nodes (up to 3 instances of t2.micro type each - Free tier eligible)
- NAT Gateway enabled
- 2 Availability Zones on N. California region, providing a higher availability of the service
- It uses the AWS module to configure both the VPC and the Kubernetes cluster

You can execute it with the Terraform Commands:

```
terraform init
```
```
terraform validate
```
```
terraform plan
```
```
terraform apply -auto-approve
```

You can change this template as per your infrastructure requirements and use this Kubernetes cluster to deploy your application on AWS.


<img width="981" height="711" alt="eks-infra-diagram" src="https://github.com/user-attachments/assets/de740e2c-2878-471d-95cf-df836d59337e" />
