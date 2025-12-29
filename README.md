# GitOps Demo Repository

## Structure
- base/ : Config globale
- apps/ : Applications (frontend, backend)
- infrastructure/ : Composants techniques
- clusters/ : Definition par environnement

## Usage
kubectl kustomize clusters/dev-cluster
kubectl kustomize clusters/prod-cluster
