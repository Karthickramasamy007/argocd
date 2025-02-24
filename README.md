# argocd
    - This install.yaml file downloaded from Argocd offial website. https://argo-cd.readthedocs.io/en/stable/operator-manual/installation/
     - Got it from Kustomize section's resources : https://raw.githubusercontent.com/argoproj/argo-cd/v2.7.2/manifests/install.yaml
     - after installation, get the passworkd from secret : kubectl get secret argocd-initial-admin-secret -n argocd -o jsonpath="{.data.password}" | base64 --decode
