# nginx-ingress-controller-module

Module built to deploy an nginx ingress controller into an EKS cluster

This module is derived from a different repository where it was building the ingress controllers as well as then deploying a load balancer.  

See https://github.com/byuoitav/terraform-kubernetes-nginx-ingress-controller (Original Repository)

We are separating them out so that this module only does one thing, deploy an Nginx Ingress Controller into the EKS cluster.  This was done so that the load balancer configuration could be more flexible and this repository could be focused on just the one task of deploying an ingress controller.  

Created: 2024-06-14