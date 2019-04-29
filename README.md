# sh commands

```sh

VERSION=${VERSION}

docker pull hawsers/kube-scheduler-amd64:${VERSION}
docker tag hawsers/kube-scheduler-amd64:${VERSION} k8s.gcr.io/kube-scheduler-amd64:${VERSION}
docker rmi hawsers/kube-scheduler-amd64:${VERSION}
```
