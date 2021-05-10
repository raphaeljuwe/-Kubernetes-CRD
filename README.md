# Kubernetes Custom Resource Definition (CRD), Accessing Kubernetes CRDs from the client-go

This readme documentation contains a guide on how to access Kubernetes CRDs
 using Go modules which integrates a third-party provider vendor into a Kubernetes 
 cluster.
 
 A client library for Custom Resource for building Kubernetes operator that  reacts on changes made to Custom Resources. 

## Setup
A kubernetes cluster needs to be provisoned initially.

Building the example:

    $ go get github.com/raphaeljuwe/-Kubernetes-CRD

Setting up a custom resource definition (CRD) with an example object:

    $ kubectl apply -f github.com/raphaeljuwe/-Kubernetes-CRD/master/kubernetes/crd.yaml
    $ kubectl apply -f github.com/raphaeljuwe/-Kubernetes-CRD/master/kubernetes/project.yaml
