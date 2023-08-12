### k8s

#### get cluster ifo
```
kubectl cluster-info
```

#### list the nodes
```
kubectl get nodes
```

#### dry run yaml mainfest
```
kubectl apply -f nginx-deploymet.yml --dry-run=client
```

#### apply yaml manifest
```
kubectl apply -f nginx-deploymet.yml 
```

#### list resources
```
kubectl get <resource type>
```

### Troubleshooting pods
#### view pod events and specs
```
kubectl describe pod <pod name>
```
#### show container logs [single container]
```
kubectl logs -f <pod name>
```
#### getting into the pod
```
kubectl exec -it  <pod name> -- <command>
```
#### show specific container log
```
kubectl logs -f <pod name> -c <container name>
```
#### list pods with IP and node details
```
kubectl get pods -o wide
```

