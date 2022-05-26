# kubeadm-installation

## server
curl https://raw.githubusercontent.com/JosephYostos/kubeadm-installation/main/master.sh |bash

## Worker
curl https://raw.githubusercontent.com/JosephYostos/kubeadm-installation/main/worker.sh |bash

## install calico CNI

kubectl create -f https://projectcalico.docs.tigera.io/archive/v3.22/manifests/tigera-operator.yaml
kubectl create -f https://projectcalico.docs.tigera.io/archive/v3.22/manifests/custom-resources.yaml
