# Azure Infrastructure Automation with Terraform 🚀

Automated provisioning and management of Azure resources (VMs, Storage, Networks) using Terraform.

---

## 📌 Project Overview

This project demonstrates **Infrastructure as Code (IaC)** practices using **Terraform** to automate **Azure infrastructure** deployments. The automation focuses on reproducibility, scalability, and best practices for cloud infrastructure. Key areas include:
- **Automate deployment of Azure Virtual Machines, Storage Accounts, Virtual Networks using Terraform**
- **Implementation of Azure Resource Manager (ARM) Templates**
- **CI/CD Pipelines with GitHub Actions & Azure DevOps**
- **Infrastructure security with RBAC, NSGs, and encryption**
- **Monitoring & cost tracking via Azure Monitor & Log Analytics**

---

## 📖 Learning Roadmap

### 🛠️ **Phase 1: Infrastructure as Code (Terraform & ARM Templates)**

- Deploy **Azure VMs** with network interfaces, security groups, and disk encryption.
- Automate networking (**VNets, Subnets, NSGs**) with Terraform modules.
- Provision **Storage** (**Blob Storage, Files, Disks**) for applications.
- Implement hybrid deployments using **ARM Templates & Terraform**.

    **📚 Relevant Courses:**
    *   [AZ-900: Microsoft Azure Fundamentals](https://www.udemy.com/course/az-900-microsoft-azure-fundamentals-with-simulations/)
    *   [AZ-104: Microsoft Azure Administrator](https://www.udemy.com/course/az-104-microsoft-azure-administrator-course-with-simulations/)
    *   [Terraform 101](https://www.udemy.com/course/terraform-101-azure-edition/)
    *   [Microsoft Learn - ARM Templates Best Practices](https://learn.microsoft.com/en-us/training/paths/deploy-manage-resource-manager-templates/)

### 🛠️ **Phase 2: Azure Kubernetes Service (AKS) Deployment**

- Deploy containerized applications using **Azure Kubernetes Service (AKS)**.
- Manage configurations with **Helm Charts**.
- Secure container storage via **Azure Container Registry (ACR)**.
- Automate deployments using **CI/CD Pipelines**.

    **📚 Relevant Courses:**
    *   [Azure Administrator: AZ-104](https://www.udemy.com/course/az-104-microsoft-azure-administrator-course-with-simulations/)
    *   [Kubernetes on Azure](https://www.udemy.com/course/terraform-on-azure-services/)
    *   [CI/CD Pipelines with GitHub Actions](https://www.udemy.com/course/learn-github-actions-ci-cd-devops-pipelines/)

### 🛠️ **Phase 3: Cloud Security & Compliance**

- Implement **IAM** (**RBAC, PIM**) for secure access control.
- Secure credentials using **Azure Key Vault**.
- Deploy **Microsoft Defender for Cloud** for workload protection.
- Enforce security with **Azure Policy & Security Center recommendations**.

    **📚 Relevant Courses:**
    *   [SC-900: Microsoft Security, Compliance, & Identity](https://www.udemy.com/course/sc-900-microsoft-security-compliance-identity-with-sims)
    *   [AZ-500: Microsoft Security Engineer](https://www.udemy.com/course/az-500-microsoft-azure-security-technologies-with-sims)
    *   [Microsoft Sentinel Course with Hands-on Labs](https://www.udemy.com/course/microsoft-sentinel-course-with-hands-on-sims/)

### 🛠️ **Phase 4: Azure Cost Optimization & Monitoring**

- Implement **Azure Monitor & Log Analytics** for performance tracking.
- Optimize cloud costs using **Azure Cost Management tools**.
- Configure **alerts & notifications** for critical events.
- Automate cost-saving techniques like **Auto-Scaling & Budget Alerts**.

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

## 📌 Next Steps

- [x] Deploy foundational Terraform infrastructure (VMs, Storage, Networking)
- [ ] Implement IAM (RBAC, PIM) & Azure Security Center
- [ ] Set up Kubernetes on AKS & containerized workloads
- [ ] Integrate monitoring & cost management (Azure Monitor, Log Analytics)
- [ ] Automate CI/CD pipelines with GitHub Actions & Azure DevOps

---

## 📌 Getting Started

- steps for environment setup and deployment instructions...

---

## 🌟 Core Skills Demonstrated

- **Cloud Environments**: Azure VMs, ARM Templates
- **IaC & Automation**: Terraform, PowerShell, Bash
- **Security & Compliance**: Network Security Groups, IAM
- **Monitoring & Cost Management**: Azure Monitor, Resource Tagging

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
