
# ⚡ Serverless Autoscaler



[![License: Mozilla Public License Version 2.0
[![Infrastructure: Terraform](https://img.shields.io/badge/Infrastructure-Terraform-623CE4.svg)](https://www.terraform.io/)
[![Runtime: Python](https://img.shields.io/badge/Runtime-Python-3776AB.svg)](https://www.python.org/)

*A lightweight serverless autoscaling solution powered by AWS Lambda and provisioned with Terraform.*


---

## 📖 About

**Serverless-Autoscaler** is an infrastructure-as-code project designed to dynamically manage and automate resource scaling. By combining **Terraform** for reproducible deployments and an **AWS Lambda (Python)** backend, it evaluates metrics and triggers adjustments to optimize performance and minimize costs.

---

## 📂 Project File Structure

```text
serverless-autoscaler/
├── .terraform/providers/          # Local Terraform provider caches (e.g., hashicorp/archive)
├── lambda/
│   ├── app.py                     # Core Python Lambda handler for autoscaling logic
│   └── app.py.save                # Backup/temporary edit file
└── README.md                      # Project documentation

🛠️ Prerequisites
Ensure you have the following installed on your machine before deploying:

Terraform (>= 1.x)

AWS CLI configured with proper permissions (aws configure)

Python 3.x (if testing code locally)

🚀 Deployment Guide
Clone the repository:

Bash
git clone 
cd serverless-autoscaler
Initialize Terraform:

Bash
terraform init
Plan the Deployment:

Bash
terraform plan
Apply Infrastructure:

Bash
terraform apply
📝 License
Distributed under the Mozilla Public License Version 2.0. 
