# Project1 CafeApp: CI/CD Automation with Jenkins, Ansible, and Kubernetes

## Overview

This project aims to streamline the Continuous Integration and Continuous Deployment (CI/CD) process by leveraging three dedicated Azure servers: Jenkins, Ansible, and Kubernetes. Jenkins is utilized for building and testing code, Ansible for automating the creation of Docker images and deployment to DockerHub, and Kubernetes for orchestrating the deployment of applications.

## Prerequisites

Before you begin, ensure you have the following components set up:

- Jenkins Server
- Ansible Server
- Kubernetes Cluster

## Setup Instructions

### Jenkins Server

1. Install Jenkins on the Jenkins server.
2. Set up Jenkins pipelines or jobs for building and testing code.
3. Configure Jenkins to trigger Ansible playbooks for further automation.

### Ansible Server

1. Install Ansible on the Ansible server.
2. Create Ansible playbooks to automate the following tasks:
   - Build Docker images.
   - Push Docker images to DockerHub.
   - Deploy Kubernetes manifests (Deployment and Service files).

### Kubernetes Cluster

1. Set up a Kubernetes cluster with the necessary nodes.
2. Ensure the Kubernetes cluster is accessible from the Ansible server.
3. Define Kubernetes manifests for your application, including Deployment and Service files.


### Usage

1. Configure Jenkins jobs or pipelines according to your requirements.
2. Execute Jenkins jobs to trigger the CI/CD process.
3. Jenkins will trigger Ansible playbooks for building Docker images, pushing to DockerHub, and deploying to Kubernetes.
4. Monitor the CI/CD pipeline through the Jenkins interface.
### Notes
Ensure proper access credentials and permissions for Jenkins to interact with Ansible and Kubernetes.
Update Ansible inventory with the necessary host details.
Customize Ansible playbooks based on your own project requirements.