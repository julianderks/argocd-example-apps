# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/julianderks/argocd-example-apps
# cd into the cloned directory
git checkout 9b5e8dccba733c45c4b7c6276f129461626e274f
helm template . --name-template dev-helm-guestbook --include-crds
```
