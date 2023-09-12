# Gke-consul
GKE Consul Helm Chart:

This helm Chart is tested on GKE - Standard Cluster .
Consul Enterprise Release - 1.16.1-ent

Steps:
1. Create a consul namespace - kubectl create ns consul
2. Apply Consul Enterprise license . [https://developer.hashicorp.com/consul/docs/k8s/deployment-configurations/consul-enterprise]
3. helm install -- helm install consul hashicorp/consul -n consul -f gke-value.yaml --wait
   
