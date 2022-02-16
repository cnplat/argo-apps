# kafka

https://www.elastic.co/guide/en/cloud-on-k8s/2.0/index.html

```shell
kubectl create -f https://download.elastic.co/downloads/eck/2.0.0/crds.yaml
kubectl apply -f https://download.elastic.co/downloads/eck/2.0.0/operator.yaml

kubectl -n elastic-system logs -f statefulset.apps/elastic-operator



```