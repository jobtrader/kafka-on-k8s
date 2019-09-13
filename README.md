# k8s kafka

## deploy zookeeper

deploy 3 node zookeeper cluster

```
# zookeeper service
kubectl create -f zk-service.yaml
kubectl get services

# create zookeeper pods
kubectl create -f zk-deployment.yaml
kubectl get pods
```

## deploy kafka

deploy 3 node kafka cluster

```
# kafka service
kubectl create -f kafka-service.yaml
kubectl get services

# kafka pods
kubectl create -f kafka-deployment.yaml
kubectl get pods
```

## delete services/pods

delete all services and pods

```
# zookeeper
kubectl delete -f zk-service.yaml
kubeclt delete -f zk-deployment.yaml

# kafka
kubectl delete -f kafka-service.yaml
kubectl delete -f kafka-deployment.yaml
```
