helm repo add jfelten https://jfelten.github.io/helm-charts/charts
helm install jfelten/gitea

# or for a more custom install
$ helm install --values custom_values.yaml --name gitea --namespace tools jfelten/gitea

