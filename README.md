# My Home Lab — GitOps

This repo contains the declarative configuration for my home lab.
Everything is deployed via ArgoCD watching this repo.

## Structure

- `bootstrap/` — Initial cluster bootstrap manifests
- `infrastructure/` — Cluster infra (ArgoCD, ingress, etc.)
- `apps/` — Application deployments

## Cluster

- K3s running on Old PC (omkarhomelaboldpc)
- ArgoCD watches this repo for changes
