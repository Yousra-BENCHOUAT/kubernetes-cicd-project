# Kubernetes Deployment & CI Project

Déploiement et administration d'une application Nginx sur un cluster Kubernetes local avec Minikube, avec haute disponibilité, stockage persistant, health checks et CI automatisée.

## Technologies

Kubernetes • Minikube • Docker • Nginx • Git • GitHub • GitHub Actions • YAML

## Fonctionnalités

- Déploiement Nginx avec 3 replicas
- Service Kubernetes et Ingress
- ConfigMap et Secret
- Liveness & Readiness Probes
- PersistentVolumeClaim (PVC)
- Scaling horizontal
- Rolling Update & Rollback
- Namespaces
- CI avec GitHub Actions
- Troubleshooting : ImagePullBackOff, CrashLoopBackOff, probes et services

## Architecture

GitHub → GitHub Actions (CI)

Client → Ingress → Service → Deployment → Pods Nginx → Persistent Storage

## CI

GitHub Actions valide automatiquement les manifests YAML lors des push et pull requests sur `main`.

## Auteur

Yousra BENCHOUAT
