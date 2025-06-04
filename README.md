# eks-with-argoCD
New project in EKS with Argo CD
Step-1:

We need to deploy the infra in Terrafoem to create the EKS cluster.

Step-2:

Install ArgoCD in the cluster with Helm charts and expose it with Load Balancer service.
Then get the user name and password for ArgoCD.

Step-3:

Write a file for ArgoCD to deploy the Nginx and point the ArgoCD to the deployment and service manifest files.
