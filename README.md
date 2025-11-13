# k8s-skiff-kustomize

Deploy your [skiff site](https://github.com/mvanduijker/k8s-skiff-site-template) with [kustomize](https://kustomize.io/).

Create your site based on [this](https://github.com/mvanduijker/k8s-skiff-site-template) template. Next step is to create your deployment based on this repository.
Change the hello-world overlay to your liking.

Deploy with:

```console
kubectl apply -k hello-world # or your overlay
```

Uninstall with:

```console
kubectl delete -k hello-world # or your overlay
```

