# Snippets day 1

## Criando  e vendo pods

```sh
kubectl run web --image=nginx
kubectl get pods
kubectl get pods -o yaml
```

## Declarativo

[[pod-nginx.yaml]]

```sh
kubectl apply -f <nome do manifesto>
kubectl delete -f  <nome do manifest
```

## Resources api

```sh
kubectl api-resources
kubectl api-versions
kubectl explain <object>
```

## Comandos interessantes

```sh
$ kubectl [-n <namespace>] get <nome do recurso>
$ kubectl [-n <namespace>] get <nome do recurso> -o yaml
$ kubectl [-n <namespace>] get <nome do recurso> -o wide
$ kubectl [-n <namespace>] describe <nome do recurso>
$ kubectl [-n <namespace>] delete <nome do recurso>
```
