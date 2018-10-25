# ks8 kafka

## deploy zookeeper

deploy 2 node zookeeper cluster

```
# zookeeper service
kubectl create -f zk-service.yaml
kubectl get services

# create zookeeper pods
kubectl create -f zk-deployment.yaml
kubectl get pods
```

## deploy kafka

deploy 2 node kafka cluster

```
# kafka service
kubectl create -f kafka-service.yaml
kubectl get services

# kafka pods
kubectl create -f kafka-deployment.yaml
kubectl get pods
```
