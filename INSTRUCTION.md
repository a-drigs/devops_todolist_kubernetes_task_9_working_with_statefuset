Run: bash bootstrap.sh

kubectl get pods -n mysql (check mysql-0 exist)
kubectl get statefulset mysql -n mysql (check Can StatefulSet create 3 pods exist)
kubectl get svc -n mysql(check headless service for statefulSet)

Go to browser http://localhost:80