# mysql

```shell
helm repo add bitnami https://charts.bitnami.com/bitnami
# 设置root密码为cnplat 初始化数据库dev 账号dev 密码dev
helm install up-mysql --set auth.rootPassword=cnplat,auth.database=dev,auth.username=dev,auth.password=dev bitnami/mysql
```