# phpmyadmin

```shell
helm repo add bitnami https://charts.bitnami.com/bitnami
# NodePort 暴露， 查询具体端口
helm install my-phpmyadmin --set service.type=NodePort  bitnami/phpmyadmin
```