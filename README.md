# 🚀 Kubernetes and Service Mesh: A Practical Guide

Welcome to the comprehensive guide for setting up Kubernetes and a service mesh with Istio from scratch. This repository is structured to make your learning experience seamless and organized.

## 📁 Directory Structure

**k8s-service-mesh-guide/**
- `README.md` - Main documentation file
- `manifests/` - Kubernetes and Istio configuration files
  - `bookinfo/` - Configurations for the BookInfo sample app
    - `deployment.yaml` - Deployment configuration for BookInfo services
    - `service.yaml` - Service configuration for BookInfo services
    - `gateway.yaml` - Gateway configuration for Istio ingress
    - `ingress.yaml` - Ingress configuration for Minikube
  - `observability/` - Monitoring and observability configurations
    - `kiali.yaml` - Configuration for Kiali dashboard
    - `prometheus.yaml` - Configuration for Prometheus
    - `grafana.yaml` - Configuration for Grafana
    - `jaeger.yaml` - Configuration for Jaeger tracing
- `scripts/` - Installation and utility scripts
  - `install_kubectl.sh` - Script to install kubectl
  - `install_minikube.sh` - Script to install Minikube
  - `install_helm.sh` - Script to install Helm
  - `install_istio.sh` - Script to install Istio
  - `generate_traffic.sh` - Script to simulate traffic for the sample app
- `docs/` - Additional documentation and guides
  - `getting_started.md` - Step-by-step setup guide
  - `kubectl_commands.md` - Common kubectl commands
  - `minikube_tips.md` - Tips and tricks for using Minikube
  - `troubleshooting.md` - Troubleshoo
