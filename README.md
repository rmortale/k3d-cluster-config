# Configuration repo of k3d clusters

Using kluctl.io [multi-env](https://kluctl.io/docs/recipes/multi-env/) as an example.


## Install
Change to the desired k8s context first! Then use kluctl deploy like:

```
kluctl deploy -t devt
```

## Secrets
This repo uses [git-crypt](https://www.agwa.name/projects/git-crypt/) to encrypt secrets.

