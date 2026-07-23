# Prometheus

## Overview

Prometheus is an open-source monitoring system that collects and stores time-series metrics from applications and infrastructure.

---

# Core Components

- Prometheus Server
- Exporters
- Service Discovery
- TSDB
- Alertmanager
- PromQL

---

# Metrics Collection

Prometheus periodically scrapes metrics from configured targets using HTTP endpoints.

Common metric sources include:

- Kubernetes
- Node Exporter
- kube-state-metrics
- Application metrics
- cAdvisor

---

# Benefits

- Pull-based architecture
- Powerful query language
- Kubernetes integration
- Native alerting support