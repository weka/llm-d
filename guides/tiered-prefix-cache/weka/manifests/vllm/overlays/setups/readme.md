Each setup is fully self-containted setup and allows switching in between them by:

`kubectl kustomize --enable-helm --load-restrictor LoadRestrictionsNone . | kubectl apply -f -`
