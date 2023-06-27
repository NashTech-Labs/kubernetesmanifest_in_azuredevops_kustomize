# kubernetesmanifest_in_azuredevops_kustomize
Use Kubernetes manifest files to deploy to clusters or even bake the manifest files to be used for deployments using Helm charts. Kustomize is an open-source configuration management tool. Kustomize can handle multiple manifests at one time.
 
 1. It will bake the yaml into the kubernetes manifest and deploy to the cluster.
 2. Azure devops offers task kubernetesmanifests@1 to deploy the manifests to the cluster.
