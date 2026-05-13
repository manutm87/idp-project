# Demo IDP Platform

## Overview
This is a hands-on Internal Developer Platform (IDP) built as a learning project.

## Stack
- **Backstage** — Developer Portal and Software Catalog
- **ArgoCD** — GitOps Continuous Deployment
- **Prometheus** — Metrics Collection
- **Grafana** — Metrics Visualization
- **Kubernetes (kind)** — Container Orchestration
- **GitHub Actions** — CI/CD Pipelines

## Architecture
The platform runs on a local Kubernetes cluster using kind with 3 nodes:
- 1 Control Plane
- 2 Worker Nodes

## Components
| Component | Purpose |
|---|---|
| Backstage | Developer portal and software catalog |
| ArgoCD | GitOps deployments |
| Prometheus | Metrics collection |
| Grafana | Metrics dashboards |

## Getting Started
1. Access the portal at http://192.168.1.23:7007
2. Browse the Software Catalog
3. Create new components using templates
4. View deployment status via ArgoCD plugin
