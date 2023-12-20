### Note

This directory is managed as per the https://argo-cd.readthedocs.io/en/stable/operator-manual/applicationset/Generators-Git/ and used to deploy application on k8s


###
```
kubectl apply -f services/git-generator.yaml -n argocd
```

```
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/applicationset/v0.4.0/manifests/install.yaml
```