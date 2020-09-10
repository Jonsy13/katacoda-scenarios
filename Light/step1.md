## Task

Firstly we will check health of our cluster and how it is running now :

`kubectl version --short && \
kubectl get componentstatus && \
kubectl get nodes && \
kubectl cluster-info`{{execute}}