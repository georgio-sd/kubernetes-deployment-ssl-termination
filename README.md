# Kubernetes deployment for SSL termination (based on custom nginx container)
- secret-setup - bash script for saving certificates as a k8s secret 
- ssl-layer.yaml - k8s deployment with mounting ssl certificates from the k8s secret
