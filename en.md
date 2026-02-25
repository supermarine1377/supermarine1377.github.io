# Ryo Koezuka

<supermarine@outlook.jp>

---

## Professional Summary

Results-oriented Senior Site Reliability Engineer (SRE) / Platform Engineer with a proven track record of eliminating operational silos and driving organizational efficiency through "Documentation as Code," data-driven operations, and advanced architecture. Adept at leveraging modern cloud ecosystems (GCP), Infrastructure as Code (Terraform), and Generative AI (LLMs) to build resilient, automated CI/CD pipelines and microservices. Excels in defining business-critical KPIs (dbt/BigQuery), enforcing architectural governance, and leading cross-functional initiatives to reduce technical debt. Passionate about transforming chaotic operational environments into highly observable, automated systems that directly impact business value.

---

## Core Competencies

* **Platform Engineering & Automation:** Architecting "Documentation as Code" pipelines (Git, CI/CD, BigQuery) to prevent knowledge degradation. Automating system evaluations and operational workflows using LLMs.
* **Data-Driven SRE:** Defining and modeling operational KGI/KPIs using dbt and BigQuery to visualize ROI and engineering toil, enabling data-driven management decisions.
* **Cloud Architecture & IaC:** Deep expertise in GCP (GKE, Cloud Run) and Terraform. Designing scalable, cost-effective microservices (Go, MongoDB) and enforcing infrastructure governance via Terraform Cloud.
* **Incident Management & Troubleshooting:** Rapidly diagnosing and resolving complex distributed system failures (network latency, GKE internals, DB bottlenecks) based on SLOs/SLIs, and implementing code-level preventative measures.
* **Technical Leadership ("Right Hand" Influence):** Enforcing security and architectural standards across development teams through CI/CD pipeline guardrails, rather than micromanagement. Successfully steering external vendors and aligning technical operations with business contracts.

---

## Technical Skills

* **Languages:** Go, SQL, Vue.js, Python (for data/AI scripting)
* **Cloud Infrastructure:** Google Cloud Platform (GKE, Cloud Run, Cloud SQL, Compute Engine, Cloud Armor, Cloud Build, Cloud Storage, Pub/Sub, Cloud Load Balancing, etc.)
* **Infrastructure as Code (IaC):** Terraform, Terraform Cloud, Helm, Docker, Kubernetes
* **Databases:** PostgreSQL, MongoDB, Redis, ElasticSearch
* **Observability & Monitoring:** Datadog, Google Cloud Monitoring
* **CI/CD:** GitHub Actions, Argo CD, CircleCI, Spinnaker
* **Data Engineering & BI:** Google BigQuery, dbt, Looker Studio
* **AI & Orchestration:** LLMs (Claude, ChatGPT API) for architecture design and CI/CD automation
* **Version Control & Collaboration:** Git, GitHub, Backlog, Slack, FigJam

---

## Professional Experience

### Insight Edge, Inc. | Tokyo, Japan

**SRE / Platform Engineer** | June 2025 – Present

Leading the modernization and automation of enterprise-wide system maintenance and operations for the Sumitomo Corporation Group's digital transformation entity. As the founding member of the OAM (Operations & Maintenance) team, architected self-sustaining operational platforms to eliminate human dependencies and reduce developer toil.

* **Documentation as Code & LLM-Driven Automation:**
  * Architected a centralized GitHub-based management system for operational manuals and service portfolios.
  * Engineered a CI/CD pipeline (GitHub Actions) to automatically sync manual data into BigQuery, ensuring operational documents are never outdated.
  * Integrated LLMs into the deployment pipeline to automatically evaluate, score, and propose improvements for operational manuals, significantly elevating company-wide documentation quality.
* **Data-Driven SRE & Observability:**
  * Defined 7 core KGI/KPIs to quantify operational burdens and vendor performance (e.g., developer involvement rate, incident lead time).
  * Modeled these KPIs using **dbt** and built automated dashboards in **Looker Studio**, providing executive visibility and successfully tracking the reduction of developer operational involvement to 63% and effort ratio to 24%.
* **Architecture Governance & NFR Standardization:**
  * Formulated a comprehensive Non-Functional Requirements (NFR) framework (Security, Availability, Maintainability) to standardize disparate project architectures.
  * Enforced infrastructure governance by mandating Terraform Cloud usage and developing plug-and-play GitHub Actions workflow templates for automated security checks.
  * Spearheaded the inventory management and update policies for AI models used across all projects, mitigating risks associated with cloud vendor deprecations.
* **Vendor Management & Incident Operations:**
  * Established robust escalation flows for both routine and non-routine tasks, successfully migrating 6 projects to external IT vendors.
  * Led weekly vendor alignment meetings, directly contributing to the optimization of contract boundaries (e.g., addressing the superficiality of 5-hour support caps).

### ZUU Co., Ltd. | Tokyo, Japan

**Software Engineer / SRE Lead** | April 2022 – May 2025

Led SRE initiatives, microservices development, and BI integrations for "MP Cloud" (a CMS for owned media, supporting ~20 tenants and 1M+ monthly PVs), managing a 4-member engineering team.

* **SRE & Incident Management:**
  * Spearheaded resolution for 10+ critical incidents (GKE troubleshooting, DB index bottlenecks, Redis scan issues, WAF blocks, VPC network failures).
  * Implemented an SLO-based monitoring framework using Datadog, prioritizing alerts based on Critical User Journeys (CUJ) to reduce operational noise.
  * Conducted root-cause analysis and pushed upstream Go code fixes to eliminate unnecessary error logs, drastically improving system observability.
* **Infrastructure Automation (IaC):**
  * Automated new tenant infrastructure provisioning using Terraform and GKE, reducing deployment time by 50% (from 16 hours to 8 hours).
* **Microservices Architecture & Development:**
  * Architected and developed an independent microservice in **Go** to manage CMS content edit history, decoupling it from the monolithic codebase.
  * Selected **Cloud Run** for cost-efficient cold starts and **MongoDB** (later migrated to GKE StatefulSet) for optimal write performance. Integrated via API Gateway.
  * Led the integration of 3D Secure authentication (Go, Vue.js), writing extensive Design Docs and executing 100+ automated/manual test cases to ensure payment security.
* **Data Engineering (Marketing Support):**
  * Built data pipelines and data warehouses using BigQuery and dbt to track business KPIs, delivering actionable Looker Studio dashboards to marketing stakeholders.

### Aqua Co., Ltd. | Tokyo, Japan

**Software Engineer** | April 2020 – March 2022

* Designed, developed, and delivered backend and frontend systems for two major outsourced client projects.
* Led the full-stack renewal of the corporate website from requirements gathering to deployment.

---

## Education

**The University of Tokyo** | Tokyo, Japan
*Master of Science in Physics* | March 2020

**Yokohama National University** | Kanagawa, Japan
*Bachelor of Science in Engineering* | March 2018

---

## Certifications

* **Applied Information Technology Engineer Examination (AP)** | Information-technology Promotion Agency, Japan (IPA) | December 2021
