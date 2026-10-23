<div align="center">

# Welcome 👋

**Cloud infrastructure · Automation · Containers · CI/CD**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge)
![Infrastructure as Code](https://img.shields.io/badge/Infrastructure_as_Code-844FBA?style=for-the-badge)
![GitOps](https://img.shields.io/badge/GitOps-EF7B4D?style=for-the-badge)

</div>

## 👨‍💻 About Me

DevOps Engineer focused on cloud infrastructure, automation and reliable deployments.

---

## ⚙️ Tech Stack

Tools I use and am developing through my projects:

| Category | Technologies |
|----------|--------------|
| **Cloud** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square) ![Amazon EKS](https://img.shields.io/badge/Amazon_EKS-FF9900?style=flat-square) |
| **Infrastructure & Configuration** | ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) |
| **Containers & Orchestration** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) |
| **CI/CD & GitOps** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) |
| **Monitoring** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) |
| **Linux & Scripting** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |

---

## 🚀 Current Project: Fider on Amazon EKS

![Project status](https://img.shields.io/badge/Status-In_Progress-FF9900?style=flat-square)

[Fider](https://github.com/getfider/fider) is an open source feedback platform. Users can submit ideas, vote on feature requests and discuss suggestions, helping teams prioritise what to build.

My project focuses on packaging, provisioning and deploying Fider on AWS. The goal is to take the application from local development to an EKS deployment with CI, GitOps and monitoring.

### 📂 Project Repositories

The project is in progress. Each repository has a separate role:

| Repository | Planned Role | Main Tools |
|------------|--------------|------------|
| **`fider-app`** | Package Fider with a multi-stage Dockerfile and run it locally with PostgreSQL and MailHog using Docker Compose. Use CI for tests, linting, image builds and Trivy scans, then publish images tagged with the commit SHA to ECR. | Docker, Docker Compose, GitHub Actions, Trivy, ECR |
| **`fider-infra`** | Provision AWS networking, EKS, RDS PostgreSQL, ECR, S3 and IAM using Terraform. Validate infrastructure changes in CI, including Checkov scans, and manage remote Terraform state in S3. | AWS, Terraform, GitHub Actions, Checkov |
| **`fider-gitops`** | Define Helm charts and environment values for dev, test and prod. Use Argo CD to sync the configuration in Git to EKS and promote the same container image through the environments. | Kubernetes, Helm, Argo CD |

### architecture diagram



<img width="1536" height="1024" alt="F98E80BA-E2DC-4F63-ACA3-100024B0139F" src="https://github.com/user-attachments/assets/ea84227d-030f-4d1a-9e60-41eeb2edc329" />


## 🔥 GitHub Contributions

![GitHub Streak](https://streak-stats.demolab.com?user=aactive1&theme=dark)










