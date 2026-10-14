# myst-node
Kubernetes manifests for deploying a Mysterium Network node (mystnodes) with ArgoCD. Includes Deployment, Service, and ArgoCD Application YAML files for automated, GitOps-driven deployment of a privacy VPN node on Kubernetes.

Add your Polygon address to Kubernetes secrets:
kubectl create secret generic myst-identity --from-literal=MYST_NODE_IDENTITY=0xYourEthereumAddress
