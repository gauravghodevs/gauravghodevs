# Gaurav Ghodage

### DevOps Engineer · SRE · Kubernetes · AWS

**Building reliable infrastructure, safer deployments, and automation for distributed systems.**

<p align="left">
  <a href="https://github.com/gauravghodevs">
    <img src="https://img.shields.io/badge/GitHub-gauravghodevs-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <a href="https://github.com/gauravghodevs/k8s-config-consumer/actions/workflows/ci.yml">
    <img src="https://img.shields.io/github/actions/workflow/status/gauravghodevs/k8s-config-consumer/ci.yml?branch=main&style=for-the-badge&label=CI" alt="CI">
  </a>
</p>

---

## 🚀 Featured Project

### Blast-Radius Guard

**Safe configuration delivery for distributed Kubernetes systems.**

A production-style DevOps/SRE engineering project that validates configuration, verifies integrity and signatures, progressively promotes changes across Kubernetes cells, monitors health, and automatically halts and rolls back unsafe releases.

**Validation → Signing → Staged Rollout → Health Gate → Automatic Rollback**

<p align="left">
  <a href="https://github.com/gauravghodevs/k8s-config-consumer">
    <img src="https://img.shields.io/badge/Project-Blast--Radius%20Guard-0A0A0A?style=for-the-badge&logo=kubernetes" alt="Blast-Radius Guard">
  </a>
  <a href="https://github.com/gauravghodevs/k8s-config-consumer/actions/workflows/ci.yml">
    <img src="https://img.shields.io/github/actions/workflow/status/gauravghodevs/k8s-config-consumer/ci.yml?branch=main&style=for-the-badge&label=Build" alt="Build status">
  </a>
  <img src="https://img.shields.io/badge/tests-28%20passing-2ea44f?style=for-the-badge&logo=pytest" alt="28 tests passing">
</p>

**Engineering highlights**

| Area | Implementation |
|---|---|
| Configuration safety | Schema + semantic validation + duplicate/dangerous-rule checks |
| Integrity | SHA-256 verification + atomic configuration handling |
| Security | Ed25519 detached signatures + signature enforcement |
| Delivery | INTERNAL → 1% → 10% → 100% staged rollout |
| Reliability | Health gates + automatic HALT → ROLLBACK |
| Recovery | Previous-config tracking + durable rollout-state recovery |
| Cloud | Versioned S3 artifacts + least-privilege IAM |
| Observability | Prometheus consumer + controller metrics |
| Automation | GitHub Actions + Terraform + Python |

**→ [Open the project](https://github.com/gauravghodevs/k8s-config-consumer)**

---

## 🧭 Architecture at a Glance

```mermaid
flowchart LR
    A[Configuration] --> B[Validate]
    B --> B1[Schema]
    B --> B2[Semantic]
    B --> B3[SHA-256]
    B --> B4[Ed25519]
    B1 --> C[Promote]
    B2 --> C
    B3 --> C
    B4 --> C
    C --> D[INTERNAL]
    D --> E[1%]
    E --> F[10%]
    F --> G[100%]
    G --> H[Health Gate]
    H -->|Healthy| I[Next Stage]
    H -->|Failure| J[HALT]
    J --> K[ROLLBACK]
    K --> L[Known-Good Config]
```

> **Design principle:** reduce blast radius before increasing exposure.

---

## 📊 Engineering Dashboard

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=gauravghodevs&show_icons=true&hide_border=true&rank_icon=github&include_all_commits=true&count_private=true" height="165" alt="GitHub statistics">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=gauravghodevs&hide_border=true" height="165" alt="GitHub streak">
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gauravghodevs&layout=compact&hide_border=true&langs_count=8" height="165" alt="Top languages">
</p>

---

## 🛠️ Technology Stack

### Cloud & Infrastructure
<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white" alt="Amazon S3">
  <img src="https://img.shields.io/badge/IAM-DD344C?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS IAM">
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform">
</p>

### Containers & Platform
<p>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Kind-2D3748?style=flat-square&logo=kubernetes&logoColor=white" alt="Kind">
</p>

### CI/CD & Observability
<p>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus">
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana">
</p>

### Engineering & Automation
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white" alt="Bash">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

---

## 🎯 What I Build

- Reliable CI/CD pipelines and deployment workflows
- Kubernetes operations and configuration delivery systems
- Infrastructure automation with Terraform
- Cloud infrastructure and AWS automation
- Observability and operational tooling
- Failure handling, rollback, and recovery mechanisms
- Security controls around configuration and releases

---

## 🔭 Current Engineering Focus

**Kubernetes · AWS · CI/CD · Observability · Infrastructure as Code · Production Automation**

I focus on understanding **why systems fail, how to reduce deployment risk, and how to automate recovery** rather than only automating the happy path.

> **Reliability over convenience. Automation over manual operations. Safe delivery over risky releases.**

---

## 📌 Featured Repository

### [Blast-Radius Guard](https://github.com/gauravghodevs/k8s-config-consumer)

`Python` · `Kubernetes` · `Docker` · `AWS S3` · `Terraform` · `Prometheus` · `GitHub Actions`

A local production-style simulation of progressive configuration delivery with validation, cryptographic signing, health-gated promotion, automatic rollback, observability, and state recovery.

**Verified project signals:** 28 automated tests · 3 Kubernetes cells · Ed25519 signing · S3 versioning · Prometheus metrics · Terraform · CI/CD

---

## 🤝 Let's Connect

I'm interested in opportunities involving **DevOps, SRE, Cloud Infrastructure, Kubernetes, Platform Engineering, and CI/CD**.

**Best way to reach me:** [GitHub profile](https://github.com/gauravghodevs)

If you're reviewing my work, start with **Blast-Radius Guard** — it is the project that best represents how I approach reliability, automation, and safe delivery.

---

<p align="center">
  <i>Build systems that are safe to change.</i>
</p>
