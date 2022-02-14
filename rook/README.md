# rook

## Github

```shell
kubectl apply -f https://raw.githubusercontent.com/cnplat/yaml/main/rook/crds.yaml
kubectl apply -f https://raw.githubusercontent.com/cnplat/yaml/main/rook/common.yaml
kubectl apply -f https://raw.githubusercontent.com/cnplat/yaml/main/rook/operator.yaml

# 二选一
# 生产存储集群的常用设置。至少需要三个工作节点。
kubectl apply -f https://raw.githubusercontent.com/cnplat/yaml/main/rook/cluster.yaml
# 未配置冗余的测试集群的设置。只需要一个节点。
kubectl apply -f https://raw.githubusercontent.com/cnplat/yaml/main/rook/cluster-test.yaml
```

## Gitee

```shell
kubectl apply -f https://gitee.com/cnplat/yaml/raw/main/rook/crds.yaml
kubectl apply -f https://gitee.com/cnplat/yaml/raw/main/rook/common.yaml
kubectl apply -f https://gitee.com/cnplat/yaml/raw/main/rook/operator.yaml

# 二选一
# 生产存储集群的常用设置。至少需要三个工作节点。
kubectl apply -f https://gitee.com/cnplat/yaml/raw/main/rook/cluster.yaml
# 未配置冗余的测试集群的设置。只需要一个节点。
kubectl apply -f https://gitee.com/cnplat/yaml/raw/main/rook/cluster-test.yaml
```