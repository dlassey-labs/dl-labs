<div align="center">

#  DL LABS – Infrastructure , Automation & AI Platform

</div>


<div align="center">

![DL-Labs](https://img.shields.io/badge/DL--LABS-INFRASTRUCTURE%20%7C%20ENGINEERING%20%7C%20AUTOMATION%20%7C%20AI-2E75B6?style=for-the-badge&labelColor=1F3864)

</div>




## 🎯 Purpose

**DL LABS is a self-hosted experimentation platform** for modern IT infrastructure, automation, and AI operations. It is designed for:

- 🔬 **Experimentation** — design and validate production-ready patterns across open-source and enterprise technologies

- 🛠 **Reference blueprints** — reusable IaC modules, playbooks, pipeline templates to enable scalable and automated deployments

- 🏗 **Real-world Enterprise scenarios** — simulate and validate production-like architectures

- 🤖 **AI integration & operations** — explore self-hosted LLMs, agents, RAG patterns and integrate intelligent automation into IT workflows


---

## 🧱 Core Stack


**Compute & Virtualization** 
- Proxmox · vSphere  · Kubernetes · Docker 

**Containers & Orchestration**  
- Docker · Kubernetes

**Infrastructure as Code & Configuration**  
- Terraform · Ansible

> *Multi-hypervisor IaC : Terraform modules and Ansible playbooks designed to work seamlessly accross Proxmox and VMware vSphere environments.*


**CI/CD & Automation**
- GitLab (self-hosted) · GitLab Runner · AWX · n8n

**Identity, Secrets & Patch Management**
- Active Directory · Vault · Canonical Landscape · Foreman   

**Network & Edge**
- OPNsense · Pi-hole · Nginx Proxy Manager · Nginx · NetBox 

**Observability & Security**
- Wazuh · Zabbix · Grafana 

**Self-Hosted AI Stack**
- Ollama · LangGraph · Qdrant · Open WebUI

**In Progress**

Currently exploring and integrating into the lab:

- **VMware Cloud Foundation (VCF)** — full SDDC stack evaluation
- **Dify** — no-code platform to build AI assistants and workflows

---

## 🏗️ Architecture

GitLab acts as the **central control plane**, orchestrating provisioning, configuration management, and CI/CD pipelines . Ansible handles Configuration Management, while Terraform manages declarative infrastructure on Proxmox.


---


## 📁 Domain Coverage

| Domain | Scope |
|---|---|
| 🛠 **INFRA** | Provisioning, Automation, IaC, Configuration management |
| 🌐 **NETWORK** | DNS, firewall, reverse proxy, segmentation |
| ⚙️ **AUTOMATION** | Workflows, RPA, scheduled jobs |
| 🧠 **AI** | Self-hosted LLMs, agents, vector search, RAG, Intelligent systems |
| 🔒 **SECURITY** | SIEM, vulnerability scanning, secrets management |
| 📦 **PLATFORM** | Containers, orchestration, service delivery |
| 📊 **OBSERVABILITY** | Metrics, logs, alerting |

---

## ⚙️ Use Cases

- **Automated VM lifecycle** — Terraform provisions, Ansible configures, AWX orchestrates
- **Patch management at scale** — Canonical Landscape with environment-based access groups, LivePatch, Foreman + Katello
- **Self-service infrastructure** — GitLab pipelines triggering parameterized AWX templates
- **AI-assisted operations** — Local LLMs (Ollama) with RAG (Qdrant) for ops documentation queries
- **Security detection** — Wazuh SIEM with custom rules and Ansible-deployed agents
- **Centralized monitoring** — Zabbix for infrastructure, Grafana for visualization

---

## 🎓 Production Experience

Beyond this experimentation platform, my hands-on experience extends to enterprise-grade environments:

![VMware vSphere](https://img.shields.io/badge/VMware_vSphere-607078?style=flat-square&logo=vmware&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Amazon Web Services](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

---

## 🚀 Roadmap

- [ ] Terraform (for Proxmox and vSphere)
- [ ] Ansible automation
- [ ] GitLab CI/CD pipeline
- [ ] AI Agent integration
- [ ] Observability stack
- [ ] Self-service provisioning portal
- [ ] Security & Governance (IAM, RBAC, Zero Trust, Secrets, PKI, SIEM)
---

## 🔄 Repository Source

> **This repository is automatically mirrored from a self-hosted GitLab instance.**  
> Active development happens upstream on GitLab. This GitHub repository serves as a 
> public showcase and portfolio reference.
>
> **Pull requests and issues are not accepted on GitHub.** For inquiries, collaboration 
> opportunities, or feedback, please reach out via the contact information below. 
 www.linkedin.com/in/dosseh-lassey
 
---

## 👤 Author

**Dosseh L**
Founder, DL-LABS | Technology and Strategic Consultant |
Infrastructure · Engineering · Automation · AI

---

*DL-Labs — Where Infrastructure Meets Intelligence* |
*Infrastructure · Engineering · Automation · AI*

 
