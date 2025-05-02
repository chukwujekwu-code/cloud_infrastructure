# cloud_infrastructure
repo for provisioning cloud infrastructure

# 🔧 chukwujekwu-code: AWS Glue Infrastructure with Terraform

This repository contains Infrastructure-as-Code (IaC) resources for setting up a complete AWS Glue environment using **Terraform**. It automates the provisioning of IAM users, S3 buckets, Glue databases, and necessary policies to support a robust data engineering workflow.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `airflow.tf` | Defines resources related to Apache Airflow integration (if applicable) |
| `exercise.tf` | Sample or test Terraform configurations for Glue |
| `gluedb.tf` | Provisions AWS Glue databases |
| `iam_policy.tf` | Custom IAM policies for fine-grained access control |
| `iam_user.tf` | IAM user creation and access key generation |
| `new_data_hub_eng_full_policy.tf` | Full-access IAM policy for Glue and related services |
| `provider.tf` | AWS provider configuration |
| `s3.tf` | S3 bucket resource definitions |
| `s3bucket.tf` | Additional S3-related resources for Glue ETL jobs |
| `usergroup.tf` | IAM user group definitions and assignments |
| `.gitignore` | Specifies intentionally untracked files |
| `LICENSE` | Project license (default or placeholder) |
| `README.md` | You’re reading it! |

---

## 🚀 Features

- ✅ **AWS Glue** job and database provisioning  
- ✅ **IAM Policy Management** for secure access  
- ✅ **S3 Buckets** for data lake storage  
- ✅ **Modular Terraform setup** for scalability and reuse  
- ✅ **Compatible with Airflow-based orchestration**

---

## 📦 Requirements

- [Terraform ≥ 1.0](https://www.terraform.io/downloads.html)
- AWS Account with sufficient privileges
- Configured AWS CLI credentials (or Terraform backend setup)

---

## 🔨 Usage

1. **Clone the Repository**
   ```bash
   git clone https://github.com/<your-username>/chukwujekwu-code.git
   cd chukwujekwu-code


