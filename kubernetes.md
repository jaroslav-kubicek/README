# Publishing docker images on Github

- [Using GitHub Packages with GitHub Actions](https://docs.github.com/en/packages/guides/using-github-packages-with-github-actions)

# Ingress controller for local development

```
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/static/provider/baremetal/deploy.yaml

kubectl get all -n ingress-nginx
```
