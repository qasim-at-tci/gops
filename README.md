## Get the code

`git clone https://github.com/qasim-at-tci/gops.git`

## ArgoCD Installation

* `kubectl create namespace argocd`
* `helm install --values ./argo-cd/values.yaml argocd ./argo-cd --namespace argocd`

## Jenkins Installation

* `kubectl create ./jenkins.yaml`
