# Deploy Applications with OpenShift GitOps (Argo CD)

*theme-park-api* contains a Helm chart for the application that will be
deployed. *gitops* contains the Argo CD manifests to deploy the Helm chart.

## Deploy

```bash
oc create -f ./gitops/manifests
```

## Undeploy

```bash
oc delete -f ./gitops/manifests
```
