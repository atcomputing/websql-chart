![My Helm Chart Logo](https://raw.githubusercontent.com/atcomputing/websql-charts/main/websql/logo.png)
# Helm chart for websql application

During the *Kubernetes Fundamentals* training, supplied by AT Computing in The Netherlands, the ``websql`` application is built.
This application consists of a ``mysql`` database server deployment and an ``apache`` web server deployment. 

This chart bootstraps both deployments on a [Kubernetes](https://kubernetes.io) cluster
using the [Helm](https://helm.sh) package manager and it supplies secrets, configmaps and a pvc/pv combination.
It considers that the database is already created on an NFS share.
