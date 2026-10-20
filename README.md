<div align="center">

Hi, I'm Nada Tahiri Alaoui 👋
DevOps & Cloud Engineering Student @ INPT

Cloud Infrastructure · Infrastructure as Code · CI/CD · DevSecOps · Observability

I build full-stack applications and the systems needed to run them: from APIs and databases to container images, automated delivery, secure cloud networking, and monitoring.

🎯 Seeking a final-year (PFE) internship in DevOps / Cloud Engineering.

Explore my repositories
</div>

👩‍💻 What I Work On
- Cloud & infrastructure: VPC networking, subnet isolation, compute provisioning, bastion access, Terraform and Ansible.
- Delivery & security: containerization, Jenkins and GitHub Actions pipelines, vulnerability and secret scanning, image registries and deployment checks.
- Reliability & observability: Prometheus metrics, Grafana dashboards, alerting, service health and operational troubleshooting.
- Software engineering: REST APIs, distributed services, databases, authentication, full-stack applications and applied AI.
🚀 Selected Projects
☁️ RoutePilot — Cloud Automation, DevSecOps & Observability on Huawei Cloud Stack
Cloud/DevOps engineering internship project · Huawei Cloud Stack

RoutePilot is an employee transportation-planning application, but the main engineering work goes beyond the application itself: building an infrastructure where it can be provisioned, secured, deployed, updated and monitored.
- Cloud architecture: designed a three-tier environment on Huawei Cloud Stack with 5 ECS instances, 5 subnets and a single VPC, separating the frontend, API, database, administration and monitoring functions. Configured security groups, private communication, SNAT/DNAT and bastion access.
- Infrastructure automation: used Terraform for provisioning and Ansible for OS setup, Docker installation, service configuration and application deployments.
- CI/CD and DevSecOps: built a Jenkins pipeline for container builds, Trivy vulnerability scans, Git-SHA image tags, publishing to GHCR, Ansible-based deployment and post-deployment checks; handled secrets through Jenkins Credentials and Ansible Vault.
- End-to-end observability: integrated Prometheus, Grafana and Alertmanager, with Node Exporter, cAdvisor, PostgreSQL Exporter, Blackbox Exporter and Express HTTP metrics.
- Application workload: React/TypeScript, Express/TypeScript, PostgreSQL/Prisma, including staff and fleet management, shift/attendance workflows and route-planning logic.
Stack: Huawei Cloud Stack Terraform Ansible Jenkins Docker Trivy GHCR Prometheus Grafana Alertmanager

Explore: Repository · Architecture · CI/CD · Observability
🚲 INPT Ride — Campus Bike & Scooter Rental Platform
End-to-end full-stack and mobile development · DevSecOps

A campus mobility platform bringing together a Django REST backend, React administration dashboard and Flutter student application. The interesting part is not just the booking interface: it includes transactional business workflows and an automated delivery process.
- Reservation consistency: used Redis-based locking and transactional overlap checks to reduce competing bookings for the same vehicle and time slot.
- Ride lifecycle and payments: implemented start/end ride transitions, time-based pricing, wallet deductions, invoice creation, payment history and notifications.
- Multi-service deployment: containerized the backend and admin dashboard with Docker Compose, PostgreSQL, Redis and Nginx for web/API routing.
- Jenkins DevSecOps pipeline: automated Gitleaks secret scans, Bandit, pip-audit, Django checks/tests and migrations, Trivy container scans, dashboard builds, smoke tests and Docker Hub publishing stages.
- Mobile development: developed a Flutter student app, with an APK-generation workflow in the mobile CI work.
Stack: Python Django REST Framework React Flutter PostgreSQL Redis Docker Jenkins Nginx Trivy

Explore: Repository · Jenkinsfile · Backend · Mobile app
❤️ MyHeart — Healthcare Platform Built with Microservices
Distributed systems · API Gateway · Kubernetes · Observability

A healthcare management system built around independent services rather than a single monolithic backend, covering patient, doctor and administrator workflows.
- Nine backend components: API Gateway plus dedicated services for authentication, patients, doctors, appointments, consultation records, billing, medical catalog and laboratory operations.
- Business workflows: role-based access, appointment scheduling with conflict prevention, consultations and prescriptions, invoices, lab requests/results and PDF report access.
- Service boundaries: REST-based communication and database-per-service design with MySQL and MongoDB.
- Containers and orchestration: a Docker Compose environment and Kubernetes resources including Deployments, Services, ConfigMaps, Secrets, readiness and liveness probes.
- Engineering operations: instrumented selected services with prom-client for Prometheus/Grafana monitoring, and added GitHub Actions CI for builds, checks and smoke tests.
Stack: Node.js Express React Prisma MySQL MongoDB Docker Compose Kubernetes GitHub Actions Prometheus Grafana

Explore: Repository and documentation · Kubernetes resources
🧠 SkillMatch AI — AI-Powered Career & Job Analysis Platform
Applied AI · Multi-step agent workflows · Vector search

A career-assistance platform combining candidate profiles and CVs with job requirements to make matching results explainable and actionable.
- Candidate analysis: PDF CV parsing, skills extraction, candidate/job compatibility, matched and missing skills, and skill-gap recommendations.
- Agentic workflows: implemented a LangGraph pipeline that connects matching, skills-gap analysis, interview preparation and LLM-based explanations.
- Retrieval and knowledge: integrated Qdrant vector search and RAG endpoints; added IT-role/skill knowledge and role recommendations.
- Job-offer analysis: supports analyzing external offer descriptions, public-source job collection with caching, and a manual-input fallback where extraction is unavailable.
- Full-stack architecture: React/Vite/Tailwind frontend, FastAPI backend, PostgreSQL and Docker Compose, with configurable AI integrations.
Stack: Python FastAPI React PostgreSQL Qdrant LangGraph RAG Sentence Transformers Docker Compose

Explore: Repository · LangGraph pipeline · RAG endpoints
💌 Letter4You — Private Digital Letters & Vaults
Full-stack development · Access control · CI/CD

A personal-letter platform built around private digital spaces and recipient access codes. The application combines a creative frontend experience with access control, expiration rules and automated container delivery.
- Application features: create and manage letter collections, compose styled letters, share spaces through generated codes, and configure anonymous sender details, expiration and open-once behavior.
- Security: JWT-based account authentication in the published version, bcrypt-hashed passwords and access codes, ownership checks and request-rate limiting.
- Data and runtime: Node.js/Express backend, PostgreSQL + Prisma, React frontend, Docker Compose and an Nginx-served frontend.
- GitHub Actions pipeline: frontend builds, Prisma generation, Hadolint, Gitleaks, Docker builds, Trivy scan reporting, and frontend/backend publishing to GHCR with commit-based tags.
Stack: React Node.js Express PostgreSQL Prisma Docker Nginx GitHub Actions Gitleaks Trivy GHCR

Explore: Repository · CI workflow · Prisma schema


Explore: Repository
🛠️ Technologies I Use
Domain	Tools and technologies
Cloud & Infrastructure	Huawei Cloud Stack, Terraform, Ansible, Linux, VPC networking, SSH
CI/CD & DevSecOps	Jenkins, GitHub Actions, Docker, Docker Compose, GHCR, Docker Hub, Trivy, Gitleaks.
Containers & Orchestration	Docker, Nginx, Kubernetes
Monitoring	Prometheus, Grafana, Alertmanager, Node Exporter, cAdvisor, Blackbox Exporter
Backend	Python, TypeScript, JavaScript, Django REST Framework, FastAPI, Node.js, Express, Prisma
Frontend & Mobile	React, Vite, Tailwind CSS, Flutter, Dart
Databases & Messaging	PostgreSQL, MySQL, MongoDB, SQLite, Redis.
Applied AI	LangGraph, RAG, embeddings, sentence-transformers



Interested in DevOps, Cloud Infrastructure, automation, and the engineering behind deployable applications.

GitHub Profile · All Repositories
</div>
