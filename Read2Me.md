


cd \kairos\

git clone https://github.com/torstenbrink/argo.git

cd .\argo\argocd-install\

helm install argocd .\argo-cd\ --namespace=argocd --create-namespace -f .\values-override.yaml


# Create forwarder manuall to login.

admin & PW see in Lens / Secrets
