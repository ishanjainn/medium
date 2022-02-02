# Folder structure for blueprint-staging

| Folder                                               |Description|
|------------------------------------------------------|------------|
| [argocd/medium](argocd/medium)                       | values.yml for ArgoCD helm installation |
| [gitops/medium](gitops/medium)                       | All *.yml files in this folder (recursive search) will be deployed to the cluster by ArgoCD aka The GitOps folder|
| [gitops/medium/monitoring](gitops/medium/monitoring) | Manifests relating to the monitoring stack |