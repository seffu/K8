kubectl apply -f mongo-config.yaml
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo.yaml
kubectl apply -f webapp.yaml


kubectl get all
kubectl get pod
kubectl get configmap
kubectl get svc
kubectl get node -o wide


