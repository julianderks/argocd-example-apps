# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/julianderks/argocd-example-apps
# cd into the cloned directory
git checkout 21f77b57b0e65e0b266312ab1bdbe3dd7aca9465
helm template . --name-template acc-helm-guestbook --include-crds
```
