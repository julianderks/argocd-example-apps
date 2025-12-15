# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/julianderks/argocd-example-apps
# cd into the cloned directory
git checkout 2348d6e1db3958a26573ef7d49849b549c115bf0
helm template . --name-template dev-helm-guestbook --include-crds
```
