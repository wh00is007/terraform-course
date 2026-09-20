# Terraform Course — Exercises

Hands-on exercises from the Udemy course
"Mastering Terraform: Beginner to Expert" by Lauro Mueller.

## Structure
- `01-benefits-iac/` — Section 3: IaC Benefits exercises
  - VPC, subnets, internet gateway, route table via Terraform
- `02-hcl/` — Section 4: HCL syntax overview
  - All 7 HCL block types: terraform, provider, resource, data, variable, output, locals, module
- `03-first-tf-project/` — Section 4: First Terraform project
  - S3 bucket with random suffix using random provider and string interpolation

## How To Use
1. Navigate into a section folder
2. Add your AWS credentials via `aws configure`
3. `terraform init`
4. `terraform plan`
5. `terraform apply`
6. `terraform destroy` when done