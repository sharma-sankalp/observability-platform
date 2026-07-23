# ServiceMonitor

## Overview

ServiceMonitor is a Custom Resource Definition (CRD) provided by the Prometheus Operator for automatically discovering Kubernetes services to scrape.

---

# Configuration

A ServiceMonitor defines:

- Namespace selector
- Label selector
- Metrics endpoint
- Port
- Scrape interval

---

# Benefits

- Native Kubernetes integration
- Automatic service discovery
- Simplified Prometheus configuration