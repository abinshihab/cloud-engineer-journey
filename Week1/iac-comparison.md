
# 📄 Infrastructure-as-Code (IaC) Comparison

_Author: Ahmed Bin Shehab_  
_Date: Week 1 – Day 3 of Cloud Engineer & Architect Journey_

---

## 🔧 What is Infrastructure as Code (IaC)?

Infrastructure as Code (IaC) is the practice of managing and provisioning infrastructure through machine-readable definition files, rather than physical hardware or interactive configuration tools. It allows for consistent, repeatable deployments of infrastructure components across environments.

---

## 🛠️ Comparison: Terraform vs CloudFormation vs ARM

| Feature                  | Terraform (HashiCorp)                        | AWS CloudFormation                     | Azure ARM / Bicep                     |
|------------------------ |-----------------------------------------------|----------------------------------------|---------------------------------------|
| 🔁 Multi-Cloud Support | ✅ Yes (AWS, Azure, GCP, OCI, etc.)           | ❌ AWS Only                            | ❌ Azure Only                         |
| 🧱 Language            | HCL (HashiCorp Configuration Language)        | JSON / YAML                            | JSON / Bicep                           |
| 🔄 State Management    | Remote/local (backend in S3, GCS, etc.)       | Managed by AWS                         | Managed by Azure                       |
| 🧰 Modularity          | High – uses modules                           | Medium – nested stacks                 | Bicep supports modules                 |
| 💬 Community Support   | Large open-source community + providers       | Strong in AWS ecosystem                | Growing in Azure ecosystem             |
| 📚 Learning Curve      | Medium – requires understanding HCL & modules | Easy if you use AWS Console regularly  | Medium – easier with Bicep             |
| 🔓 Open Source         | ✅ Yes                                        | ❌ AWS proprietary                     | ❌ ARM is proprietary, Bicep is OSS     |

---

## 📝 Summary & Decision

After reviewing the three options, I've decided to focus on **Terraform** first due to its:

- ✅ Multi-cloud flexibility
- ✅ Strong modular structure
- ✅ Huge open-source ecosystem
- ✅ Real-world usage in DevOps/Platform roles

I'll revisit CloudFormation and Bicep later for AWS/Azure-specific projects.

---

## 📎 Resources
- [Terraform Docs](https://developer.hashicorp.com/terraform/docs)
- [AWS CloudFormation](https://docs.aws.amazon.com/cloudformation/index.html)
- [Azure Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview)

---
📌 Part of my 8-week journey to become a Cloud Engineer & Architect.

