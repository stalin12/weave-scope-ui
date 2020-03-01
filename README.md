# weave-scope-ui

Weave-scope is a user interface for Kubernetes Cluster.
It provides all the information of the cluster in the graphical format.

Steps to set up the weave-scope-ui

1. Execute below kubectl command in the Kubernetes cluster.
   kubectl apply -f weavescope.yaml
2. Wait for all the Kubernetes objects gets up.
   To know if everything is up and running execute
   kubectl get all -n weave
3. Once everything is up execute below kubectl command to start the weave-scope service
   kubectl apply -f scope-service.yaml
4. Once weave-scope UI is up and running then use the below url to access the UI
   http://IP_ANY_NODE_OF_CLUSTER:30081/
 
