 <div align="center">

<h1>Welcome 👋</h1>

<strong>Cloud Infrastructure · Automation · Containers · CI/CD</strong>

<p>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge" alt="AWS"/>
  <img src="https://img.shields.io/badge/Infrastructure_as_Code-844FBA?style=for-the-badge" alt="Infrastructure as Code"/>
  <img src="https://img.shields.io/badge/GitOps-EF7B4D?style=for-the-badge" alt="GitOps"/>
</p>

</div>

## 👨‍💻 About Me

DevOps Engineer focused on cloud infrastructure, automation and reliable deployments.

I enjoy working with AWS, Terraform, Kubernetes and CI/CD technologies with a focus on understanding how infrastructure and application delivery work together.

---

## ⚙️ Tech Stack

| Category | Technologies |
|---|---|
| **Cloud** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square) ![Amazon EKS](https://img.shields.io/badge/Amazon_EKS-FF9900?style=flat-square) |
| **Infrastructure & Configuration** | ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) |
| **Containers & Orchestration** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) |
| **CI/CD & GitOps** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) |
| **Security** | ![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square) ![Checkov](https://img.shields.io/badge/Checkov-4F46E5?style=flat-square) ![AWS Secrets Manager](https://img.shields.io/badge/Secrets_Manager-DD344C?style=flat-square) |
| **Monitoring** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square) |
| **Linux & Scripting** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |

---

## 🚀 Featured Project: Fider on Amazon EKS

![AWS EKS](https://img.shields.io/badge/Platform-Amazon_EKS-FF9900?style=flat-square)
![Terraform](https://img.shields.io/badge/IaC-Terraform-844FBA?style=flat-square)
![GitOps](https://img.shields.io/badge/Deployment-GitOps-EF7B4D?style=flat-square)

[Fider](https://github.com/getfider/fider) is an open-source feedback platform where users can submit ideas, vote on feature requests and discuss suggestions. Helping teams prioritise what to build.

I built a cloud deployment around Fider using AWS and Kubernetes, focusing on infrastructure provisioning, containerisation, CI/CD automation, GitOps and monitoring.

### 🏗️ Architecture Overview

<div align="center">
  <img
    src="https://github.com/user-attachments/assets/ea84227d-030f-4d1a-9e60-41eeb2edc329"
    width="750"
    alt="Fider EKS Architecture"
  />
</div>

### 🔄 How It Works

1. **Terraform** provisions the VPC, EKS cluster, RDS PostgreSQL, ECR, IAM and supporting AWS resources.
2. **GitHub Actions** runs application checks, security scans and Docker image builds.
3. **Amazon ECR** stores container images tagged with their Git commit SHA.
4. **Argo CD and Helm** manage Fider deployments across development, test and production environments.
5. **External Secrets Operator** retrieves application credentials from AWS Secrets Manager.
6. **Prometheus and Grafana** provide Kubernetes monitoring, while CloudWatch monitors AWS services.

### 📂 Project Repositories

| Repository | Implementation | Main Tools |
|---|---|---|
| **[fider-app](https://github.com/aactive1/fider-app)** | Multistage Docker builds, local PostgreSQL and MailHog setup, automated CI checks, Trivy scans and container image publishing to ECR. | Docker, GitHub Actions, Trivy, ECR |
| **[fider-infra](https://github.com/aactive1/fider-infra)** | AWS networking, EKS, RDS, IAM, remote Terraform state in S3 and infrastructure security checks. | AWS, Terraform, Checkov |
| **[fider-gitops](https://github.com/aactive1/fider-gitops)** | Helm deployments, Argo CD, dev/test/prod image promotion, External Secrets Operator and Kubernetes monitoring. | Kubernetes, Helm, Argo CD, Prometheus, Grafana |

### 📖 Documentation

**Infrastructure**
- [AWS Architecture & Terraform Configuration](https://github.com/aactive1/fider-infra)
- [Infrastructure Deployment Runbook](https://github.com/aactive1/fider-infra/blob/main/docs/runbook.md)

**Application**
- [Docker & CI/CD Configuration](https://github.com/aactive1/fider-app)
- [GitHub Actions Workflows](https://github.com/aactive1/fider-app/tree/main/.github/workflows)

**Kubernetes & GitOps**
- [Helm, Argo CD & Monitoring](https://github.com/aactive1/fider-gitops)
- [Kubernetes Deployment Runbook](https://github.com/aactive1/fider-gitops/blob/main/docs/runbook.md)

---

## 🔥 GitHub Contributions

<div align="center">
  <img src="https://streak-stats.demolab.com?user=aactive1&theme=dark" alt="GitHub Streak"/>
</div>













