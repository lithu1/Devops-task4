# Devops-task4
# 🚀 DevOps Task 3: Infrastructure as Code (IaC) with Terraform

# Objective
Provision a Docker container running Nginx using Terraform as Infrastructure as Code.

# Tools Used
- Terraform
- Docker
- AWS EC2 (Ubuntu 22.04 LTS)

#  Files Included
- `main.tf` – Terraform script to provision Docker container
- `execution_logs.txt` – Output logs from terminal (init, plan, apply, destroy)
- `screenshots/` – Screenshots of successful provisioning (optional)

# Steps Performed

1. **Launched AWS EC2 instance**
2. **Installed Docker & Terraform**
3. Wrote `main.tf` to:
   - Pull Nginx Docker image
   - Create and run a container
   - Expose port 8080 for access
4. Ran:
   - `terraform init`
   - `terraform plan`
   - `terraform apply`
5. Verified Nginx running on `http://51.20.60.177:8080`
6. Cleaned up using `terraform destroy`

# Access
After applying the Terraform config, Nginx was accessible at:
![image](https://github.com/user-attachments/assets/50a2227c-0cc3-41cb-bd20-ca86ed69c0a5)

