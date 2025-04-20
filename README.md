# application-deployment

Ce dépôt contient les fichiers de configuration pour déployer l’application `humidity-prediction` sur un cluster Kubernetes.

## Structure

- `deployment/deployment.yaml` : déploiement du container Docker
- `deployment/service.yaml` : service interne au cluster
- `deployment/ingress.yaml` : accès externe via URL

## Utilisation

```bash
kubectl apply -f deployment/
