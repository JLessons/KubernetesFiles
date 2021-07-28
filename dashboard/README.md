# How to run dashboard ?

 - Set up your cluster (Make sure your kubectl recognizes your cluster)
 - run `kubectl apply -f dashboard.yaml`
 - execute `kubectl proxy`
 - access from web browser:
     - http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/#/login
 