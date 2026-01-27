# Project Development History & Conditions

## Project Overview
This project is a Full-stack Todo Application integrated with AI Agents, containerized with Docker, and orchestrated using Kubernetes (Minikube).

---

## Development Phases

### Phase 1: API Development
- Built a robust Todo API using **FastAPI** and **SQLModel**.
- Implemented CRUD operations for task management.

### Phase 2: AI Agent Integration
- Integrated **OpenAI Agents** to provide smart task suggestions.
- Enabled AI-powered chat functionality within the application.

### Phase 3: Containerization
- Created optimized **Dockerfiles** for Backend, Agent, and Frontend.
- Orchestrated the local stack using **Docker Compose**.

### Phase 4: Kubernetes Orchestration
- Developed K8s manifests including **Deployments**, **Services**, and **Secrets**.
- Managed local cluster deployments using **Minikube**.

### Phase 5: Cloud Deployment & Registry
- Migrated local database to **Neon Serverless Postgres** for cloud connectivity.
- Tagged and pushed images to **Docker Hub** with `phase5` tags for global accessibility.
- Implemented `imagePullPolicy: Always` in manifests to ensure cloud-sync.

---

## Deployment Conditions
1. **Docker Desktop**: Must be running for local image management.
2. **Minikube**: Required for local Kubernetes cluster testing.
3. **Registry**: Images are pulled from `docker.io/rabiawaheed/`.
4. **Environment**: Database URL and API keys must be configured in `secrets.yaml`.