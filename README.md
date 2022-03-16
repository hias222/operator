# operator Test

operator

## install

operator-sdk create api --group cache --version v1alpha1 --kind Memcached --resource --controller

bin/kustomize build config/crd | kubectl apply -f -
customresourcedefinition.apiextensions.k8s.io/memcacheds.cache.hias222.org created