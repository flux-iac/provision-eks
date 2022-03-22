# provision-eks

Products Used: Terraform, TF-controller

EKS or the Amazon Elastic Kubernetes Service is an AWS service for creating, and managing Kubernete clusters.

In this tutorial, you will deploy an EKS cluster using GitOps and Terraform. Then, you will configure `kubectl` to connect to the cluster using information obtained from an Terraform output.


> :warning: **Warning!** An EKS cluster pricing starts from $0.10 per hour. You may be charged a few dollars by running this tutorial, but we are not responsible for any charges that may incur.

## Why deploy with GitOps and Terraform?



## Prerequisites

This tutorial assumes that you are familar with Kubernetes and `kubectl` command. But It does not assume that you have an existing cluster deployment.

This tutorial also assumes that you are familiar with basic use of Terraform like `plan` and `apply` workflow. If you are new to Terraform, please refer to this tutorial.

This tutorial also assumes that you know basic knowledge of GitOps, but does not assume any previous GitOps hands-on experience.

