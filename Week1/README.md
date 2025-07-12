# Week 1 – Infrastructure as Code (IaC) & Terraform Fundamentals

Welcome to **Week 1** of my 8-Week DevOps & Platform Engineer Challenge.

This week focuses on mastering Infrastructure as Code (IaC) principles and building a reusable VPC module with Terraform.

---

## 📌 Goals

- Understand the core concepts of IaC
- Compare major IaC tools: Terraform, AWS CloudFormation, Azure Bicep
- Write a clean and reusable Terraform VPC module
- Test and validate the module using a root configuration

---

## 📁 Folder Structure

week1/
├── README.md                     ← Summary of Week 1 (this file)
├── iac-comparison.md            ← Notes comparing Terraform, CloudFormation, and Bicep
└── terraform-vpc-module/        ← Reusable Terraform VPC module
    ├── main.tf                  ← VPC resource definitions
    ├── variables.tf             ← Input variables for the module
    ├── outputs.tf               ← Output values (e.g., VPC ID, subnet IDs)
