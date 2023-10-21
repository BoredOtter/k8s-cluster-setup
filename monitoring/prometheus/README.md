To install prometheus:
1. kubectl create -f prometheus-bundle.yaml
2. kubectl apply -f rbac.yaml 
3. kubectl apply -f prometheus.yaml
4. kubectl apply -f service.yaml
5. kubectl apply -f prometheus_servicemonitor.yaml





kubectl create namespace monitoring
kubectl create -f https://raw.githubusercontent.com/prometheus-operator/prometheus-operator/master/bundle.yaml
