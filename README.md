# Global Tech LLC Application

Auto-generated application managed by OpenLuffy.

## Stack
- **Language**: Golang
- **Framework**: net/http
- **Container Registry**: GitHub Container Registry (GHCR)

## Environments
- **Development**: `global-tech-llc-dev` namespace
- **Pre-production**: `global-tech-llc-preprod` namespace  
- **Production**: `global-tech-llc-prod` namespace

## Local Development

### 

## CI/CD Pipeline
GitHub Actions automatically builds and deploys on push:
- `develop` branch → DEV + PREPROD environments
- `main` branch → PRODUCTION environment (manual approval required)

## Deployment
Managed by ArgoCD - syncs automatically when new images are pushed.

## Health Check
All environments expose `/healthz` endpoint for liveness/readiness probes.

---
*Managed by OpenLuffy* 🏴‍☠️
