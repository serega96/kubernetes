Check **kube-apiserver** -  `cat /etc/kubernetes/manifests/kube-apiserver.yaml`

`kubectl get roles`

`kubectl get rolebindings`

#### **Create role**
`kubectl create role <name> --verb=list,get --resource=development`
