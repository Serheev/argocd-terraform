# Module to deploy Higly Availabe ArgoCD via HelmChart to EKS

Example to use:

```
module "argocd" {
  source           = "./terraform_argocd_eks"
  eks_cluster_name = "demo-dev"
  chart_version    = "6.4.0"
}
```