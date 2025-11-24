<h1 align="center">👋 I’m Asad</h1>

<p align="center">
<strong>Cloud & Platform Engineer | AWS • Terraform • GitOps • Kubernetes • CI/CD</strong>
</p>

---

### About Me

I’m a project-led cloud/platform engineer who builds **production-aligned AWS platforms**, systems that are **boring, stable, and secure by default**.

I focus on:

- AWS environments that are **hardened from day one**
- **Git-driven infrastructure** with Terraform and modular design
- Delivery pipelines that are **predictable, auditable, and fully automated**
- Observability and security woven into the platform, not bolted on

My background in data analytics means I think deeply about the **data layer, access boundaries, and security automation** that modern applications rely on.

---

### Stack

**Cloud & Platform (core):**  
AWS (IAM, VPC, EKS, Lambda, S3, CloudWatch, Step Functions, Batch), Terraform, Docker, Kubernetes

**Delivery & GitOps:**  
GitHub Actions, Argo CD, CI/CD pipelines, OIDC GitHub → AWS auth

**Security & Governance:**  
IAM least-privilege, CI-based scanning, observability, policy as code

**Data Foundations:**  
Databricks, Spark, Airflow, Glue, Athena

**Languages:**  
Python, SQL, PowerShell



---

# My Current **Projects**


### 🚀 Nimbus Signals  
**A production-aligned, GitOps-driven AWS platform running a real-time price microservice.**

**Why this matters:**  
Shows I can design and operate a full Kubernetes platform on AWS with Terraform, Argo CD, observability, and CI/CD.

**Highlights:**  
- FastAPI service ingesting live BTC/ETH prices with structured logging and health probes  
- Kubernetes runtime on **EKS** with separate namespaces for app, monitoring, and platform components  
- **GitOps delivery** through Argo CD (all cluster state managed from Git)  
- Terraform modules for **VPC, EKS, node groups, IAM, ECR, networking**  
- End-to-end **CI/CD** via GitHub Actions (build → test → push → Helm updates)  
- Full observability: **kube-prometheus-stack + Grafana dashboards** for app + platform metrics

🔗 Repo: https://github.com/asads-cloud/nimbus-signals

---

### 🎧 Nimbus Transcribe  
**A cloud-native, GPU-accelerated transcription pipeline using AWS serverless + Batch.**

**Why this matters:**  
Demonstrates distributed systems thinking, cost-aware design, and orchestrating GPU workloads at scale using AWS Step Functions + Batch.

**Highlights:**  
- End-to-end pipeline: **S3 → Lambda → Step Functions (Distributed Map) → AWS Batch GPU → Lambda stitcher → S3**  
- **Dockerised Whisper** running on GPU-backed Batch compute for parallel, high-throughput transcription  
- Tuned for **performance vs cost** (configurable model sizes, concurrency, instance types)  
- **Terraform-first** deployment across accounts/regions  
- **GitHub Actions** for CI/CD (image builds, packaging, deploy automation)  
- Designed as an example of **distributed systems + applied ML + IaC** working together

🔗 Repo: https://github.com/asads-cloud/nimbus-transcribe

---

### 🛡️ Nimbus Guard  
**A multi-region AWS security scanner built for CI/CD pipelines and DevSecOps workflows.**

**Why this matters:**  
Shows practical cloud security engineering: scanning, automated reporting, GitHub → AWS OIDC, and security gating in pipelines.

**Highlights:**  
- Detects high-risk misconfigurations across S3, IAM, EC2, VPC, CloudTrail, and account settings  
- Built to run in **CI/CD** with **OIDC-based GitHub → AWS authentication**  
- Outputs **Markdown, HTML, and JSON** reports for PR comments or dashboards  
- Implements **severity-based gating** (fail CI on HIGH/CRITICAL findings)  
- Distributed as a **Dockerised Python 3.12 CLI**, with least-privilege IAM roles provisioned via Terraform  
- Represents a compact but realistic **cloud security automation pipeline**

🔗 Repo: https://github.com/asads-cloud/nimbus-guard

---

> More infra/platform engineering projects coming, I prefer real builds over buzzwords.

---

###  What I’m Learning Right Now

- Hardening AWS environments with **SCPs, Config rules, IAM baselines**  
- Strengthening **GitOps workflows** with Argo CD & Terraform  
- Kubernetes observability: metrics, logs, dashboards, actionable alerts  
- Designing **cost-efficient** cloud environments  

---

###  Connect with me on:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Asad%20Rana-blue?logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/in/asad-rana-9b01161b9/)  
[![Email](https://img.shields.io/badge/Email-asad.rana0016%40gmail.com-red?logo=gmail&logoColor=white&style=flat-square)](mailto:asad.rana0016@gmail.com)
