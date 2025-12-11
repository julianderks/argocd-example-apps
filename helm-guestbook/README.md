# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/julianderks/argocd-example-apps
# cd into the cloned directory
git checkout a6397eeddcf73f76002a9b0e250dcc53e504f151
helm template . --name-template dev-helm-guestbook --include-crds
```
