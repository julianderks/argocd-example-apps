# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/julianderks/argocd-example-apps
# cd into the cloned directory
git checkout 464797b33d526127d547adeb16b555b4fd2ede19
helm template . --name-template dev-helm-guestbook --include-crds
```
