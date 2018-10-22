# ks8 kafka

## deploy zookeeper

deploy 3 node zookeeper cluster

```
# zookeeper service
kubectl create -f zookeeper-service.yaml
kubectl get services

# create zookeeper pods
kubectl create -f zookeeper-pod.yaml
kubectl get pods
```

## deploy kafka

deploy 3 node kafka cluster

```
# kafka service
kubectl create -f kafka-service.yaml
kubectl get services

# kafka pods
kubectl create -f kafka-pod.yaml
kubectl get pods
```
