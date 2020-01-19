 kubectl apply -f mysql-database-data-volume-persistentvolumeclaim.yaml
 kubectl apply -f mysql-deployment.yaml
 kubectl apply -f mysql-service.yaml
 
 kubectl apply -f todo-web-application-config-map.yaml
 kubectl apply -f todo-web-application-secret.yaml
 kubectl apply -f todo-web-application-deployment.yaml
 kubectl apply -f todo-web-application-service.yaml
 
 kubectl apply -f ingress-controller-config-map.yaml
 kubectl apply -f ingress-resources.yaml
 kubectl apply -f ingress-controller.yaml
 kubectl apply -f ingress-service.yaml
 
 
 
 
 
 