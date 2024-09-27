* Pod
```
kubectl apply -f hello-kube.yaml
```

```
kubectl get pod -l app=hello-kube
```

```
kubectl delete pod {name}
```

```
minikube image load {name}
```

```
 kubectl delete pod {name}
```

```
kubectl describe pod {name} -n {namespace}
```

```
kubectl port-forward -n {namespace} pod/{name} {exposePort}:{portContainer} 
```
