#### prints the version of minikube
```
minikube version
```
### starts a local Kubernetes cluster
```
minikube start
```
### access the Kubernetes dashboard running within the minikube cluster in browser
```
minikube dashboard
```
#### retrieves the IP address of the minikube
```
minikube ip
```
#### logs into the minikube environment (for debugging)
```
minikube ssh
```
#### stops minikube
```
minikube stop
```
#### points your shell to minikube's docker-daemon  --> to avoid image pull from registry
```
eval $(minikube docker-env)
```
#### use hosts resources
  add an entry in containers **/etc/hosts** file **host.minikube.internal** <ip>

