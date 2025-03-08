# Azure Infrastructure Automation with Terraform 🚀

Automated provisioning and management of Azure resources (VMs, Storage, Networks) using Terraform.

---

## 📌 Project Overview

This project demonstrates **Infrastructure as Code (IaC)** practices using **Terraform** to automate **Azure infrastructure** deployments. The automation focuses on reproducibility, scalability, and best practices for cloud infrastructure. The project emphasis is on:
- **Automate deployment of Azure Virtual Machines, Storage Accounts, Virtual Networks using Terraform.**
- **Implement Azure Resource Manager (ARM) Templates.**
- **Use GitHub Actions / Azure DevOps for CI/CD Pipelines.**
- **Secure infrastructure with RBAC, NSGs, and encryption.**
- **Set up monitoring & cost tracking using Azure Monitor & Log Analytics.**

---

## 📖 Learning Roadmap

### 🛠️ **Phase 1: Infrastructure as Code (Terraform & ARM Templates)**

- **Deploy Azure VMs** with network interfaces, security groups, and disk encryption.
- **Automate networking (VNets, Subnets, NSGs)** with Terraform modules.
- **Storage provisioning** (Blob Storage, Files, Disks) for applications.
- **Use ARM Templates & Terraform together** for hybrid deployment.

    **📚 Relevant Courses:**
    *   [AZ-900: Microsoft Azure Fundamentals](https://www.udemy.com/course/az-900-microsoft-azure-fundamentals-with-simulations/), [AZ-104: Microsoft Azure Administrator](https://www.udemy.com/course/az-104-microsoft-azure-administrator-course-with-simulations/)
    *   [Terraform 101](https://www.udemy.com/course/terraform-101-azure-edition/)
    *   [Microsoft Learn - ARM Templates Best Practices](https://learn.microsoft.com/en-us/training/paths/deploy-manage-resource-manager-templates/)

### 🛠️ **Phase 2: Azure Kubernetes Service (AKS) Deployment**

- **Containerized app deployment** using Azure Kubernetes Service.
- **Implement Helm Charts** for managing configurations.
- **Use Azure Container Registry (ACR)** for secure image storage.
- **Set up CI/CD pipelines** to deploy Kubernetes manifests.

    **📚 Relevant Courses:**
    *   [Azure Administrator: AZ-104](https://www.udemy.com/course/az-104-microsoft-azure-administrator-course-with-simulations/)
    *   [Kubernetes on Azure](https://www.udemy.com/course/terraform-on-azure-services/)
    *   [CI/CD Pipelines with GitHub Actions](https://www.udemy.com/course/learn-github-actions-ci-cd-devops-pipelines/)

### 🛠️ **Phase 3: Cloud Security & Compliance**

- **Implement IAM (RBAC, PIM)** for resource security.
- **Use Azure Key Vault** for secrets management.
- **Deploy Microsoft Defender for Cloud** to protect workloads.
- **Create & enforce Azure Policy & Security Center recommendations.**

    **📚 Relevant Courses:**
    *   [SC-900: Microsoft Security, Compliance, & Identity](https://www.udemy.com/course/sc-900-microsoft-security-compliance-identity-with-sims)
    *   [AZ-500: Microsoft Security Engineer](https://www.udemy.com/course/az-500-microsoft-azure-security-technologies-with-sims)
    *   [Microsoft Sentinel Course with Hands-on Labs](https://www.udemy.com/course/microsoft-sentinel-course-with-hands-on-sims/)

### 🛠️ **Phase 4: Azure Cost Optimization & Monitoring**

- **Set up Azure Monitor & Log Analytics** to track VM & AKS performance.
- **Use Azure Cost Management tools** to optimize billing.
- **Configure alerting rules & notifications** for critical events.
- **Automate cost-saving techniques** using Auto-Scaling & Budget Alerts.

    **📚 Relevant Courses:**
    *   [Troubleshooting Microsoft Azure Connectivity](https://www.udemy.com/course/az-720-troubleshooting-microsoft-azure-connectivity-course/)
    *   [Microsoft Applied Skills: Configure Secure Azure Networking](https://www.udemy.com/course/microsoft-applied-skills-configure-secure-access-to-your/)
    *   [Azure Monitor & Cost Management Documentation](https://www.udemy.com/course/azure-infrastructure-managing-cost-governance-monitoring/)

---

## 📂 Repository Structure

```bash
Azure-Infrastructure-Automation/
│── README.md                   # Overview & Getting Started
│── Terraform/
│   ├── main.tf                  # Core Terraform configuration
│   ├── variables.tf              # Variables & Inputs
│   ├── outputs.tf                # Outputs & Exports
│   ├── modules/
│   │   ├── networking.tf         # VNet, Subnets, NSGs
│   │   ├── storage.tf            # Storage Account, Disks
│   │   ├── compute.tf            # VMs, AKS Cluster
│── CI-CD/
│   ├── github-actions.yml        # GitHub Actions CI/CD pipeline
│   ├── azure-pipelines.yml       # Azure DevOps CI/CD pipeline
│── Security/
│   ├── rbac.tf                   # IAM Roles, RBAC policies
│   ├── encryption.tf             # Storage & VM Disk Encryption
│   ├── azure-policy.tf           # Security & Compliance Policies
│── Monitoring/
│   ├── azure-monitor.tf          # Metrics & Log Analytics
│   ├── alert-rules.tf            # Alerts & Budget Notifications
│── LICENSE
│── Journal.md                   # Weekly Progress Tracking

```

---



## 🌟 Core Skills Demonstrated

- **Cloud Environments**: Azure VMs, ARM Templates
- **IaC & Automation**: Terraform, PowerShell, Bash
- **Security & Compliance**: Network Security Groups, IAM
- **Monitoring & Cost Management**: Azure Monitor, Resource Tagging

---

## 📌 Getting Started

- steps for environment setup and deployment instructions...

---

## 🤝 Contributing & Collaboration

- Fork and create a branch
- Commit clear and descriptive changes
- Submit a pull request

I’m open to collaborating on **Cloud Infrastructure**, **DevOps projects**, and **automation initiatives**. Feel free to connect for collaboration or knowledge exchange!

---

## 📜 License

Content and projects within this repository are licensed under the [MIT License](LICENSE).

---

## 📧 Contact & Connect

📩 **Email**: [natureuplift@protonmail.com](mailto:natureuplift@protonmail.com)  
<!-- 🔗 **LinkedIn**: [Arnaldo Sepulveda](https://www.linkedin.com/in/arnaldo-sepulveda) -->
