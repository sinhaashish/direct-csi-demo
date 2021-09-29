# direct-csi-demo
```
alias k3s="kubectl --kubeconfig /home/ashish/.kube/k3s.yaml"
k3s get pods -n direct-csi-min-io
./kubectl-direct_csi --kubeconfig /home/ashish/.kube/k3s.yaml drives ls --all
k3s delete -f minio.yaml
k3s delete pvc  --all
```

### Uninstall
```
 ./kubectl-direct_csi --kubeconfig /home/ashish/.kube/k3s.yaml uninstall --crd --force
 ```
 
 ### Install
```
 ./kubectl-direct_csi --kubeconfig /home/ashish/.kube/k3s.yaml --image direct-csi:v1:4:1
 ```
  ### Install usin my own registru 
```
 ./kubectl-direct_csi --kubeconfig /home/ashish/.kube/k3s.yaml --org sinha1 --image direct-csi:v1
 ```
 
 ### get nodes 
 ```
 k3s get nodes 
 ```
