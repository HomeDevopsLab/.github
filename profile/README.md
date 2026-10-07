<div align="center">

<img src="media/banner.svg" alt="Home DevOps Lab — production-grade platform engineering, running at home" width="100%">

GitOps-driven Kubernetes, Infrastructure as Code and observability,<br>
built and operated like a real product, on hardware you can own.

[![Docs](https://img.shields.io/badge/docs-docs--lab.angrybits.pl-2563eb?style=for-the-badge&logo=readthedocs&logoColor=white)](https://docs-lab.angrybits.pl)
[![GitOps](https://img.shields.io/badge/GitOps-Flux%20CD-5468ff?style=for-the-badge&logo=flux&logoColor=white)](https://fluxcd.io)
[![Location](https://img.shields.io/badge/based%20in-Poland-dc2626?style=for-the-badge)](#)

</div>

---

## 🚀 What we do

Home DevOps Lab is an engineering playground with production habits. Every service is declared in Git, every change goes through a pipeline, and every component is monitored. The result is a set of reusable building blocks you can lift into your own lab — or your day job.

| | |
|---|---|
| ⚙️ **GitOps first** | The cluster state lives in Git. Flux CD reconciles it, Renovate keeps it fresh, SOPS keeps secrets safe. |
| 🏗️ **Infrastructure as Code** | Proxmox VMs, cloud resources on AWS and Azure — all provisioned with Terraform, Terragrunt and Ansible. |
| 📈 **Observability built in** | Prometheus, Grafana, Alertmanager and log aggregation from day one, not as an afterthought. |
| 🔐 **Security by default** | Secrets in Vault and SOPS, TLS everywhere via cert-manager and Let's Encrypt, tested backups. |
| 🏠 **Self-hosted & independent** | Own your data and your platform — no vendor lock-in, no surprise changes to terms of service. |

## 📦 Open-source building blocks

| Project | What it is | Stack |
|---|---|---|
| [**appchart**](https://github.com/HomeDevopsLab/appchart) | One reusable Helm chart for every app — services, ingress with TLS, volumes, probes and Flux image automation. | `Helm` `Flux CD` `Traefik` |
| [**iac-tools**](https://github.com/HomeDevopsLab/iac-tools) | Batteries-included CI image with Terraform, Terragrunt, Ansible, Vault, `gh` and `glab`. | `Docker` `Terraform` `Ansible` |
| [**tfmodule-ses**](https://github.com/HomeDevopsLab/tfmodule-ses) | Terraform module for AWS SES — sending and receiving mail on your own domain. | `Terraform` `AWS` |
| [**docs**](https://github.com/HomeDevopsLab/homedevopslab.github.io) | Source of the lab knowledge base, published at [docs-lab.angrybits.pl](https://docs-lab.angrybits.pl) (PL / EN). | `VuePress` `Docker` |

## 🧭 Under the hood

<img src="media/architecture.svg" alt="Platform architecture: Git drives CI pipelines, a container registry, Flux CD and Kubernetes with observability; Terraform provisions AWS, Azure and Proxmox; Renovate keeps dependencies up to date" width="100%">

## 🛠️ Tech stack

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Flux](https://img.shields.io/badge/Flux%20CD-5468FF?style=flat-square&logo=flux&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Renovate](https://img.shields.io/badge/Renovate-1A1F6C?style=flat-square&logo=renovate&logoColor=white)

## 💡 Why a homelab?

> The fastest way to learn the cloud is to run one yourself.

A homelab lets you experiment with the latest technologies without public-cloud bills, safely test solutions before they reach production, and keep full control over your own data.

---

<div align="center">

**[📖 Read the docs](https://docs-lab.angrybits.pl)** · **[⭐ Star a project](https://github.com/orgs/HomeDevopsLab/repositories)** · **[💬 Open an issue](https://github.com/HomeDevopsLab/appchart/issues)**

</div>
