# Kubernetes init
A initialization script to provision a kubernetes cluster with Cilium CNI and metalLB

## Usage
# Cluster
curl -s https://raw.githubusercontent.com/joepvand/KubernetesInit/main/create-cluster.sh | sh -

# LoadBalancer (metal-lb)
- wget https://raw.githubusercontent.com/joepvand/KubernetesInit/main/create-metalLb.sh
- chmod +x create-metallb.sh
- ./create-metallb.sh 192.168.1.1/24 (Replace with actual IP range)
