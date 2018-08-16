# kubeprom-operator
A simple way to deploy Kube Prometheus and Prometheus Operator on K8s.

# Purpose

When I tryed yo deploy Kube-prometheus and Prometheus Operator on K8S I take a little while. Sometimes, we dont have much time to deploy things, so I made a couple of annotations about it and maybe this things can help someone else to deploy Kube-Prometheus, Prometheus Operator and new services on Prometheus.

# References

This manifests were taked from: 

- https://github.com/coreos/prometheus-operator
- https://github.com/coreos/prometheus-operator/tree/master/contrib/kube-prometheus

# Requirements

- Kubernetes Cluster UP and Running;
- Acess to K8S API using kubectl.

# How to Deploy Kube-Prometheus
```
- Clone this repo
- cd manifests/kube-prometheus
- kubectl apply -f .
```
