# LAB-APPS

Lab apps-of-apps

This laboratory share a scenario for installation the cluster openshift using Gitops.
The instalation use kustomization, kustomize and helm and for this configuration required a secret that contain metadata the cluster with sensible data, that`s a secret in project openshift-config. 

# Reference

## RHACM - Policy Generator
 
#### Integrating the Policy Generator with OpenShift Container Platform GitOps (Argo CD):
- https://docs.redhat.com/en/documentation/red_hat_advanced_cluster_management_for_kubernetes/2.10/html-single/gitops/index#gitops-service-account-argo-cd
 
## Configure Generator to download from cluster:
- https://access.redhat.com/articles/7049658
 
## PolicyCollection:
- https://github.com/open-cluster-management-io/policy-collection
 
## Overview:
- https://github.com/stolostron/policy-generator-plugin
 
## Binários:
- https://github.com/open-cluster-management-io/policy-generator-plugin/releases
 
## Category NIST based:
- https://csrc.nist.gov/projects/cprt/catalog#/cprt/framework/version/SP_800_53_5_1_1/home
 
 
## Based configuration

#### Repositories Git:
 
##### Gitops + RHACM + Kustomize:
- https://github.com/bry-tam/acm-create-clusters-policies
 
##### GitOps for organizations: provisioning and configuring Openshift clusters automatically
- https://github.com/albertogd/gitops-for-organizations

##### GitOps Catalog
- https://github.com/redhat-cop/gitops-catalog.git
 
## Articles:
 
#### Tips for using templating in Governance Policies
- https://www.redhat.com/en/blog/tips-for-using-templating-in-governance-policies-part-1
- https://www.redhat.com/en/blog/tips-for-using-templating-in-governance-policies-part-2
 
#### Provisioning OpenShift clusters using GitOps with ACM
- https://www.redhat.com/en/blog/provisioning-openshift-clusters-using-gitops-with-acm
- https://www.redhat.com/en/blog/gitops-for-organizations-provisioning-and-configuring-openshift-clusters-automatically?extIdCarryOver=true&sc_cid=701f2000001Css5AAC
- https://www.redhat.com/en/blog/configuring-openshift-cluster-with-applicationsets-using-helmkustomize-and-acm-policies?extIdCarryOver=true&sc_cid=701f2000001Css5AAC

## Documentation

#### Functions policies RHACM
- https://docs.redhat.com/en/documentation/red_hat_advanced_cluster_management_for_kubernetes/2.4/html/governance/governance#template-functions
