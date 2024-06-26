Pre requirements for deploying Kubeflow with the DeployKF project can be found here:
https://www.deploykf.org/guides/getting-started/


The steps to follow in short:

1) Setup a Kubernetes cluster
2) Install ArgoCD
3) Configure the app-of-apps.yaml manifest to reflect your environments requirements
4) Apply the "Argo application" manifest app-of-apps.yaml to the argocd namespace
5) Run the sync_argocd_app.sh script to make sure all Kubeflow components are deployed in the right order