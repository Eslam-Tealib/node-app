## Project Overview

A CI/CD pipeline for deploying a simple NodeJS application on Kubernetes. 

### Project Features
* Creating Cluster on AWS using IaC
* Deploy Jenkins on Kubernetes using Ansible
* CI/CD for a simple NodeJS app using Jenkins

---
## Deploying Approach
### Step 1: Creating Minikube Cluster Locally
* Applying `minkube start` command to create the cluster

### Step 2: Deploy Jenkins on Kuberbnetes using Ansible
* Automate deploy using Ansible Playbook.
* Deploy Jenkins in Kubernetes.

### Step 3: CI/CD pipeline for a simple app using Jenkins
* Creating Pipeline for simple Hello app.
* Deploy simple Hello app (Locally).


Note: `Jenkinsfile` file contains all the details about the pipelines
