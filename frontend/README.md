markdown
# Hackathon Todo App Submission (Phase 4 & 5)

This project is a comprehensive multi-phase hackathon application featuring a Next.js frontend, a FastAPI backend, and an integrated AI Agent.

## 🚀 Project Overview
- **Phase 1-3:** Core Todo functionality and state management.
- **Phase 4:** AI Agent integration with specialized logic and Dockerization.
- **Phase 5:** Cloud-native architecture with Kubernetes (K8s) manifests and CI/CD readiness.

## 🛠️ Tech Stack
- **Frontend:** Next.js
- **Backend:** Python (FastAPI / UV)
- **AI Integration:** OpenAI API / LangChain
- **Infrastructure:** Docker & Docker Compose
- **Orchestration:** Kubernetes (K8s)

## 🏗️ Architecture & Deployment
The application is structured to run as a set of interconnected microservices:
- **Frontend Service:** Handles the user interface.
- **Backend Service:** Manages the API and business logic.
- **AI Agent Service:** Specialized service for intelligent task handling.

### How to Run (Local Docker)
```bash
docker-compose up --build

```

### Kubernetes (Phase 5)

Manifests are located in the `/k8s` directory for cloud-native deployment:

* `deployment.yaml`
* `service.yaml`
* `secrets.yaml` (Placeholders included for security)

## 📺 Demo Video

[Click here to watch the Phase 4 & 5 Demo Video](https://drive.google.com/file/d/15vr5FfYkBk8pMeokEO2WUffh6ybkfGSX/view?usp=drive_link)
*(Due to cloud provider verification delays, a full functional demo is provided via video).*

## 👤 Author

**Rabia Waheed**

