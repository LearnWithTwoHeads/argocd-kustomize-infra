# ArgoCD Sample repo

This repository demonstrates a seamless way of deploying software onto a Kubernetes cluster, leveraging ArgoCD's cool feature of [application sets](https://argo-cd.readthedocs.io/en/latest/user-guide/application-set/).

We leverage the git files generator to continuously deploy applications to our cluster by writing YAML. Each application will be an ArgoCD application, and its up to the cluster administrator to define what will be inside each application.
