# Texas Votes
Code of infrastructure, scripts and Kibana dashboards to collect and index early voter turnout data. This code powers https://texasvotes.invertedorigin.com

## Before you install you must have the following
* Elastic Cloud on Kubernetes (ECK) - https://github.com/elastic/cloud-on-k8s
* A Kubernetes Ingress Controller - https://kubernetes.github.io/ingress-nginx/

## Installation
```
git clone git@github.com:keatontaylor/texasvotes.git
cd deploy
kubectl apply -f .
```
