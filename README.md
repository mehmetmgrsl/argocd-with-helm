# Test argocd


1. kubectl create namespace argocd

2. kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

3. kubectl apply -f argocd-cm.yaml

4. kubectl apply -f my-apps.yaml


Note-1: This repo has been cloned from https://gitlab.com/ayush-sharma/example-assets

Note-2: https://argo-cd.readthedocs.io/en/stable/operator-manual/upgrading/1.7-1.8/#health-assessement-of-argoprojioapplication-crd-has-been-removed has been applied to use app-of-apps pattern and orchestrating synchronization using sync waves. (Step 3 above)



# Using an external Helm values


1. kubectl apply -f helm-app.yaml