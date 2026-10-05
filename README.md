# Terraform Docker Infrastructure as Code

## Task 3: Infrastructure as Code (IaC) with Terraform

### Objective
Provision and manage a local Docker container using Terraform.

### Tools Used
- Terraform
- Docker
- Git
- GitHub

### Infrastructure Created
Terraform was used to create an Nginx Docker container.

- Container name: terraform-nginx
- Docker image: nginx:alpine
- Internal port: 80
- External port: 8081

### Terraform Commands Used

```bash
terraform init
terraform fmt
terraform validate
terraform plan
terraform apply -auto-approve
terraform state list
terraform destroy -auto-approve