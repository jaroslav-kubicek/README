# Publishing docker images on Github

- [Publishing Docker images](https://docs.github.com/en/actions/guides/publishing-docker-images)
- [Using GitHub Packages with GitHub Actions](https://docs.github.com/en/packages/guides/using-github-packages-with-github-actions)

# Ingress controller for local development

Taken from [How to Expose Your Services With Kubernetes Ingress](https://betterprogramming.pub/how-to-expose-your-services-with-kubernetes-ingress-7f34eb6c9b5a)

```
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/static/provider/baremetal/deploy.yaml

kubectl get all -n ingress-nginx
```
