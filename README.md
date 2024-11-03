# K8s-nti-lab2
1- How many Namespaces exist on the system?

2- How many pods exist in the kube-system namespace?

3- Create a deployment with

Name: beta

Image: redis Replicas: 2

Namespace: finance

Resources Requests:

CPU: 500m

Mem: 1G

Resources Limits:

CPU: 1

Mem: 2G

4- Apply a label color=blue to the master node

5- Create a new deployment named blue with the nginx image and 3 replicas

Set Node Affinity to the deployment to place the pods on master only NodeAffinity: required During SchedulingIgnored During Execution

Key: color

values: blue

6- Create a namespace named "iti" with a resource quota on pods "2"

7- Create a deployment named "nginx" with image "nginx", replicas 3 on the "iti" namespace

8- How many pods have been created within the nginx deployment and why?

9- Create LimitRange for the "gold" namespace with memory (limit: 500 Mi, request: 200 Mi)

10- Create a pod named "ingot" in the "gold" namespace
