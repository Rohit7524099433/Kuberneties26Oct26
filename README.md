# Kuberneties26Oct26

green.yaml
blue.yaml
service.yaml

kubectl apply -f blue.yaml
kubectl apply -f green.yaml
kubectl apply -f service.yaml

kubectl get deploy
kubectl get svc

kubectl get nodes -o wide

for i in {1..10}; do curl -s http://172.30.2.2:30080 | grep h1; done
