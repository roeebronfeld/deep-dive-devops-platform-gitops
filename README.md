# deep-dive-devops-platform-gitops

This is the GitOps repository for the platform.

The app repository contains the application code and the Helm chart. This repository contains environment-specific deployment values.

`dev` and `staging` each override a small set of Helm values for their respective environments.

ArgoCD is intended to use this repository as the desired state source.
