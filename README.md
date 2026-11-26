# microservices-gitops

Бажаний стан застосунку для Argo CD.

- `bootstrap/` — кореневий Application (App of Apps)
- `argocd-apps/` — Application застосунку
- `charts/microservices/` — Helm-чарт, значення для minikube у `values-minikube.yaml`

Secret `app-secrets` створюється в namespace `microservices` вручну і в Git не зберігається.
