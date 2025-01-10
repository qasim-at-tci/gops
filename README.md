## ArgoCD Installation

* `kubectl create namespace argocd`
* `helm install --values ./argo-cd/values.yaml argocd ./argo-cd --namespace argocd`