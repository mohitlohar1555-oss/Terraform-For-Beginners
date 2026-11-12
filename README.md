# 🚀 Terraform for Beginners

## 📘 Introduction

Welcome to **Terraform for Beginners**!

This repository contains beginner-friendly documentation about **Terraform and Infrastructure as Code (IaC)**. It explains how Terraform helps DevOps engineers automate, create, manage, and provision cloud infrastructure using code.

## 🌍 What is Terraform?

Terraform is an Infrastructure as Code (IaC) tool developed by HashiCorp. It allows you to define and manage infrastructure using configuration files written in **HCL (HashiCorp Configuration Language)**.

## 🎯 Why Use Terraform?

- ⚡ Automate infrastructure provisioning.
- 🔄 Create repeatable and consistent environments.
- ☁️ Support multiple cloud platforms.
- 📦 Manage infrastructure through code.
- 🔍 Preview infrastructure changes using `terraform plan`.
- 🤝 Collaborate using Git and version control.
- 💰 Reduce manual infrastructure management.

## ⭐ Advantages of Terraform

- Declarative Configuration
- Multi-Cloud Support
- Infrastructure Automation
- Reusable Modules
- Dependency Management
- State Management
- Version Control Integration
- CI/CD Integration

## 💻 Language Used

Terraform uses **HCL (HashiCorp Configuration Language)**.

Configuration files use the `.tf` extension.

Example:

```hcl
resource "aws_s3_bucket" "my_bucket" {
  bucket = "my-example-terraform-bucket"
}
```

## 🔄 How Terraform Works

1. **Write** – Create Terraform configuration files.
2. **Initialize** – Download required providers.
3. **Plan** – Preview infrastructure changes.
4. **Apply** – Create or update infrastructure.

## 🛠️ Important Terraform Commands

| Command | Description |
|---|---|
| `terraform init` | Initialize Terraform |
| `terraform fmt` | Format configuration files |
| `terraform validate` | Validate configuration |
| `terraform plan` | Preview changes |
| `terraform apply` | Apply changes |
| `terraform destroy` | Destroy managed infrastructure |
| `terraform output` | Display output values |
| `terraform state list` | List managed resources |

## 📚 Core Terraform Concepts

- Provider
- Resource
- Data Source
- Variables
- Outputs
- Modules
- State
- Backend
- Workspace

## ⚖️ Terraform vs Other Tools

- Terraform – Infrastructure provisioning.
- Ansible – Configuration management.
- AWS CloudFormation – AWS infrastructure management.
- Pulumi – Infrastructure as Code using programming languages.
- OpenTofu – Open-source Terraform fork.

## 🔐 Terraform Best Practices

- Use remote state with locking.
- Never upload `terraform.tfstate` to GitHub.
- Keep sensitive information secure.
- Use reusable Terraform modules.
- Validate configurations before applying.
- Review the execution plan before deployment.
- Use version control for configuration files.

## 📂 Repository Contents

```text
terraform-for-beginners/
│
├── README.md
└── Terraform_IaC_Documentation_Mohit_Gadilohar.pdf
```

## 🎓 Learning Outcome

After studying this documentation, beginners will understand Terraform fundamentals, Infrastructure as Code, HCL, Terraform commands, workflows, advantages, and best practices.

## 👨‍💻 Author

**Mohit Gadilohar**

🎯 Aspiring Cloud & DevOps Engineer

🔗 LinkedIn: (www.linkedin.com/in/mohit-gadilohar-devops)

💻 GitHub: (https://github.com/mohitlohar1555-oss)

---

⭐ If you find this repository helpful, don't forget to give it a Star!

**Keep Learning | Keep Building | Keep Growing 🚀**
