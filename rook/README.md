# 说明
rook-ceph 是提供 operator 安装, 先安装 operator 然后在创建一个 crd 到集群内。
# 修改 rook-ceph-cluster/values.yaml
关键信息在 nodes: 下面， 修改每一个主机的磁盘信息
# 安装方式
```bash
cd rook-ceph
./install.sh
cd ../rook-ceph-cluster
./install.sh
```
