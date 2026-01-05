# my-argocd-poc-gitops
my-argocd-poc-gitops will contain all the manifest spec files of my applications

This Repo will contain all the values and kustomization files for my applications


## argocd-apps folder
argocd-apps folder contains all the argocd application spec files for every cluster and environment

## base folder
base folder contains all the helm chart files for every application
- TODO: Helm charts should reside in another repository and push to a helm chart repository
- TODO: Patch the Argocd Application spec files to use the helm chart repository with targetRevision as the Chart version

## clusters folder
clusters folder contains all the Helm chart values files for every cluster and environment

# TODO: Application Set
- Change this setup to Application Set Generator
