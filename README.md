# DevOps Observability Lab

Production-grade observability and monitoring stack built using Docker Compose.

## Stack

- Prometheus
- Grafana
- Node Exporter
- cAdvisor
- Blackbox Exporter
- Jenkins
- Docker Compose

## Features

- Infrastructure monitoring
- Container monitoring
- Uptime monitoring
- HTTP endpoint probing
- Dynamic Grafana dashboards
- Prometheus alerting
- Blackbox monitoring
- Docker metrics collection
- CPU and memory alerts
- Container health monitoring

## Architecture

Docker Containers
↓
Node Exporter + cAdvisor + Blackbox Exporter
↓
Prometheus
↓
Grafana Dashboards + Alerting

## Dashboards

### Infrastructure Dashboard
- CPU usage
- Memory usage
- Disk usage
- Network traffic

### Container Dashboard
- Container CPU
- Container memory
- Container network metrics

### Uptime Dashboard
- Endpoint availability
- Response time
- HTTP status monitoring

## Run Project

```bash
docker compose up -d
```
