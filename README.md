# argocd-notification

## kubectl get configmap argocd-notifications-cm -n argocd -o yaml > argocd-notifications-cm.yaml
## kubectl logs -l app.kubernetes.io/name=argocd-notifications-controller -n argocd