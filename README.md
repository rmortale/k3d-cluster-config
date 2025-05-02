# Configuration repo of k3d clusters

Using kluctl.io [multi-env](https://kluctl.io/docs/recipes/multi-env/) as an example.


## Install
Change to the desired k8s context first! Then use kluctl deploy like:

```
kluctl deploy -t devt
```

## Secrets
This repo uses [git-crypt](https://www.agwa.name/projects/git-crypt/) to encrypt secrets. Add secrets to .gitattributes before adding them to the repo!

How-to [manage your secrets](https://dev.to/heroku/how-to-manage-your-secrets-with-git-crypt-56ih)

### git-crypt error: libssl missing
Install with:
```
wget http://nz2.archive.ubuntu.com/ubuntu/pool/main/o/openssl/libssl1.1_1.1.1f-1ubuntu2.24_amd64.deb && sudo dpkg -i libssl1.1_1.1.1f-1ubuntu2.24_amd64.deb
```
