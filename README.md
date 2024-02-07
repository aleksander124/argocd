## Basic repo for argocd application config

All applications are build for kubernetes env. argocd was used to automate the process of deploying applications to a kubernetes cluster and to simply modify objects on the cluster using the ```everything as a code``` method.

This is a simplified version of multicluster management using argocd - in this case only one cluster was used based on the corresponding labels on argocd secrets (cluster secret created when adding a new cluster) 