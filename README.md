# aprendiendo-minikube

wget https://storage.googleapis.com/minikube/releases/latest/minikube_latest_amd64.deb

helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update
helm install prometheus prometheus-community/prometheus
