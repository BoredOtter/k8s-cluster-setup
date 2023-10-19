Cluster Setup

1. Nginx:
    `Provided by Digital Ocean as a one-click app.`
2. Certmanager:
    `kubectl apply -f https://github.com/cert-manager/cert-manager/releases/download/v1.13.1/cert-manager.yaml`
3. Metrics Api:
    `kubectl apply -f https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/high-availability-1.21+.yaml`