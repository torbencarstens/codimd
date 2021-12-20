# codimd

## Installation

```bash
$ helm upgrade --install --wait --atomic codimd codimd/codimd --set "postgresql.postgressPassword=__POSTGRES_PASSWORD__,storageClass=longhorn,service.type=ClusterIP,codimd.imageStorePersistentVolume.size=1Gi"
$ helm install codi-utils . --atomic --wait
```
