# Orange-Kubernetes

---

# Kubernetes Tasks and Labs - Orange Egypt

Welcome to my repository showcasing the Kubernetes tasks and labs I completed during my time at Orange Egypt. This repository includes various Kubernetes configurations, deployments, and other related tasks that demonstrate my experience with Kubernetes.


## Overview

This repository contains Kubernetes configurations and scripts for various tasks and labs I worked on. The purpose of these tasks is to enhance my understanding and practical skills in managing Kubernetes clusters and deploying applications.

## Setup

To get started with these Kubernetes tasks, follow these steps:

1. **Install Kubernetes**: Make sure you have a Kubernetes cluster set up (e.g., Minikube, kind, or a managed Kubernetes service).
2. **Configure kubectl**: Ensure that your `kubectl` is configured to communicate with your Kubernetes cluster.

## Tasks and Labs

### NodePort Service

This section includes configurations for exposing a Kubernetes deployment using a NodePort Service. 

- **Deployment Name**: `backend`
- **Service Type**: NodePort

### Multi-Port Service

Here, you'll find configurations for a Kubernetes Service that exposes multiple ports (e.g., HTTP and HTTPS) on a deployment.

- **Deployment Name**: `multi-port-app`
- **Ports Exposed**: 80 (HTTP) and 443 (HTTPS)

### Pod with hostPath Volume

This task involves setting up a Pod that mounts a `hostPath` volume to access files from the host node's file system.

- **Volume Type**: hostPath
- **Purpose**: Access files from the host node's file system

### ConfigMap as Volume

In this section, you can see how to use a ConfigMap as a volume in a Kubernetes Pod.

- **Purpose**: Mount a ConfigMap as a volume in a Pod to provide configuration data

### PersistentVolumeClaim Resizing

This task demonstrates how to resize a PersistentVolumeClaim (PVC) in Kubernetes.

- **Objective**: Request more storage for a PVC


---

Feel free to adjust the content as needed to better fit your specific tasks and labs!
