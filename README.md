<h1 align="center">Hi, I'm Nada Tahiri Alaoui 👋</h1>
<h3 align="center">Cloud & DevOps Engineering Student · INPT Rabat</h3>

<p align="center">
  Cloud Infrastructure · Infrastructure as Code · CI/CD · DevSecOps · Observability
</p>

<p align="center">
  I build applications and the infrastructure that runs them—from APIs and databases to automated deployments, security checks, and monitoring.
</p>

<p align="center">
  🎯 Seeking a final-year (PFE) internship in <strong>Cloud / DevOps Engineering</strong>
</p>

---

## About Me

I'm an engineering student at **INPT Rabat** with an interest in **cloud infrastructure, DevOps, backend engineering, and platform reliability**. I like projects where software development and operations meet: designing a useful application, deploying it in a realistic environment, automating the delivery process, and making it observable.

My projects span **Huawei Cloud Stack and AWS**, as well as containerized and Kubernetes-based environments. I focus on understanding the decisions behind each architecture rather than collecting tools for their own sake.

## Featured Projects

### ☁️ [RoutePilot](https://github.com/Nadaaath/routepilot)
**Huawei Cloud Stack · Infrastructure Automation · DevSecOps · Observability**

A transportation-planning application used as the workload for an end-to-end cloud infrastructure and operations project.

- Designed a segmented **Huawei Cloud Stack** environment with **five ECS instances, five subnets**, security groups, NAT, and bastion-based management access.
- Defined infrastructure with **Terraform** and used **Ansible** for host configuration, application deployment, and monitoring setup.
- Implemented a **Jenkins** delivery workflow to build Docker images, run **Trivy** vulnerability scans, publish images to **GHCR**, deploy to HCS, and perform health checks.
- Integrated **Prometheus, Grafana, Alertmanager**, and exporters for infrastructure, containers, PostgreSQL, and HTTP availability.

**Technologies:** `Huawei Cloud Stack` `Terraform` `Ansible` `Jenkins` `Docker` `GHCR` `Trivy` `Prometheus` `Grafana`

> The Jenkins Trivy stage reports HIGH/CRITICAL findings; its current configuration does not fail builds on those findings.

---

### 💌 [Letter4You](https://github.com/Nadaaath/letter-for-you)
**AWS Serverless Migration · Cloud Infrastructure · AWS-Native CI/CD**

Re-architected an existing React/Express application from Docker and PostgreSQL into an AWS serverless application for creating and sharing private digital letters.

- Deployed the **React/Vite frontend** on private **Amazon S3**, delivered over HTTPS with **CloudFront**, including same-origin `/api/*` routing.
- Adapted the **Express backend** to **AWS Lambda** behind **API Gateway HTTP API**, replacing Prisma/PostgreSQL persistence with three **DynamoDB** tables.
- Provisioned application infrastructure using **AWS SAM and CloudFormation**, with scoped **IAM** policies and secret retrieval from **Systems Manager Parameter Store**.
- Built **CodePipeline/CodeBuild** workflows with backend unit tests, reviewed CloudFormation change sets, manual approval, and post-deployment tests against the live AWS API.
- Configured **CloudWatch** metrics, a dashboard, API access logs, a 5xx alarm, and account-level budget alerts.

**Technologies:** `AWS Lambda` `API Gateway` `S3` `CloudFront` `DynamoDB` `SAM` `CloudFormation` `CodePipeline` `CodeBuild` `CloudWatch`

---

### 🚲 [INPT Ride](https://github.com/Nadaaath/INPT-Ride)
**Full-Stack Campus Mobility · DevSecOps · Kubernetes & GitOps**

A bike and scooter rental platform with a **Flutter student app**, **React admin dashboard**, and **Django REST Framework API**.

- Developed workflows for reservations, rides, wallet-based billing, invoices, notifications, and admin operations.
- Used **PostgreSQL** for persistent data and **Redis reservation locks** to reduce concurrent booking conflicts.
- Created **Jenkins DevSecOps** pipelines with **Gitleaks, Bandit, pip-audit, Trivy**, backend tests, smoke tests, and Docker Hub publishing.
- Added **Kubernetes manifests for Minikube**, an **Argo CD GitOps** configuration, and **SonarCloud** analysis through GitHub Actions.

**Technologies:** `Django REST Framework` `React` `Flutter` `PostgreSQL` `Redis` `Docker` `Jenkins` `Kubernetes` `Argo CD` `SonarCloud`

---

### ❤️ [MyHeart](https://github.com/Nadaaath/Myheart_Hospital_Project)
**Healthcare Platform · Microservices · Containerization & Kubernetes**

A healthcare management system organized around independently developed backend services and a centralized API Gateway.

- Developed workflows for **patients, doctors, and administrators**, including appointments, consultation records, billing, and lab requests/results.
- Organized services around separate responsibilities, with **MySQL** for relational domains and **MongoDB** for laboratory data.
- Containerized the application using **Docker Compose**, and created **Kubernetes Deployments, Services, ConfigMaps, Secrets, and health probes**.
- Added **GitHub Actions CI** with build and application smoke checks.

**Technologies:** `Node.js` `Express` `React` `MySQL` `MongoDB` `Docker Compose` `Kubernetes` `GitHub Actions`

> Prometheus/Grafana work is described in the project history, but the current default branch does not contain the monitoring configuration needed to reproduce it.

---

### 🧠 [SkillMatch AI](https://github.com/Nadaaath/skillmatch-ai)
**AI-Powered Recruitment Matching · LangGraph · Semantic Retrieval**

A recruitment and career-guidance platform for analyzing CVs, comparing candidate profiles with job offers, and explaining skill gaps.

- Built a **FastAPI** backend and **React** frontend with **PostgreSQL**, JWT authentication, and role-based access for candidates, recruiters, and administrators.
- Implemented **PDF CV parsing, skills extraction, candidate/job matching, and job-offer analysis** with a manual-input fallback.
- Added **LangGraph** workflows for matching, skills-gap analysis, interview preparation, and AI explanations.
- Integrated **sentence-transformers** embeddings, **Qdrant** vector search, and experimental **RAG** endpoints for context-based questions.

**Technologies:** `Python` `FastAPI` `React` `PostgreSQL` `LangGraph` `Qdrant` `sentence-transformers` `Docker Compose`

---

## Technical Stack

- **Languages:** Python · JavaScript · TypeScript · Dart · SQL
- **Cloud:** AWS · Huawei Cloud Stack (HCS)
- **AWS:** Lambda · API Gateway · S3 · CloudFront · DynamoDB · IAM · SAM · CloudFormation · CodePipeline · CodeBuild · CloudWatch · Systems Manager
- **Backend:** Django REST Framework · FastAPI · Node.js / Express
- **Frontend & mobile:** React · Vite · Flutter
- **Data:** PostgreSQL · MySQL · MongoDB · Redis · SQLite · Qdrant
- **Infrastructure & delivery:** Terraform · Ansible · Docker · Docker Compose · Jenkins · GitHub Actions · Kubernetes · Argo CD
- **Security & quality:** Trivy · Gitleaks · Bandit · pip-audit · SonarCloud
- **Monitoring:** Prometheus · Grafana · Alertmanager · CloudWatch

## Current Focus

I'm strengthening my skills in **cloud architecture, infrastructure automation, secure delivery pipelines, and observability**, while continuing to build backend and full-stack applications as realistic infrastructure workloads.

[Explore my repositories](https://github.com/Nadaaath?tab=repositories)
