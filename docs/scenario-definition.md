# Scenario Definition

## Use Case
Small Dev/Test Kubernetes cluster for DevOps portfolio workloads.

## Objectives
- Compare multi-cloud operational cost
- Evaluate control plane pricing models
- Analyze network egress impact
- Identify enterprise trade-offs

## Cluster Requirements

- 3 Worker Nodes
- 2 vCPU per node
- 4 GB RAM per node
- 50 GB disk per node
- 1 Public Load Balancer
- 200 GB monthly egress
- No autoscaling
- On-demand pricing only
- Single region deployment

## Intended Workloads
- CI/CD test pipelines
- Sample microservices
- Observability stack (Prometheus + Grafana)
- GitOps experimentation (ArgoCD)

## Evaluation Criteria

- Monthly cost
- Control plane pricing
- Network transfer model
- IAM maturity
- Terraform provider stability
- Enterprise SLA
