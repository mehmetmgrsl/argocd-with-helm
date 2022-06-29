# Test argocd

1. kubectl apply -f argocd-cm.yaml

2. kubectl apply -f my-apps.yaml


This repo has been cloned from https://gitlab.com/ayush-sharma/example-assets

Note: https://argo-cd.readthedocs.io/en/stable/operator-manual/upgrading/1.7-1.8/#health-assessement-of-argoprojioapplication-crd-has-been-removed has been applied to use app-of-apps pattern and orchestrating synchronization using sync waves.