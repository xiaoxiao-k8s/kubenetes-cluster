# kubernetes-cluster
Building Kubernetes-cluster using vagrant

```
git clone https://github.com/seungh0/kubenetes-cluster

cd kubenetes-cluster

vagrant up

vagrant status

---
Current machine states:
kmaster                   running (virtualbox)
kworker1                  running (virtualbox)
kworker2                  running (virtualbox)


# kmaster 노드에 접속
vagrant ssh kmaster

# 아래는 확인 명령어

kubectl get nodes

---
NAME       STATUS   ROLES    AGE   VERSION
kmaster    Ready    master   53m   v1.19.2
kworker1   Ready    <none>   50m   v1.19.2
kworker2   Ready    <none>   47m   v1.19.2

```

### Reference
https://blog.exxactcorp.com/building-a-kubernetes-cluster-using-vagrant/
