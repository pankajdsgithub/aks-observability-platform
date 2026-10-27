# AKS Observability Platform

This repository provides a reference observability baseline for Azure Kubernetes Service using Prometheus, Grafana, Azure Monitor integration, and SRE-friendly alerts.

```mermaid
flowchart LR
    A[AKS Workloads] --> B[Prometheus]
    B --> C[Grafana]
    A --> D[Azure Monitor]
    C --> E[Dashboards and Alerts]
```
