# Kubernetes KIND Lab

A hands-on Kubernetes learning repository using KIND (Kubernetes IN Docker).

## Overview

This repository contains:

* KIND cluster configurations
* Multi-node Kubernetes setup
* Kubernetes YAML manifests
* Practice deployments and services
* Notes and experiments while learning Kubernetes

## Prerequisites

* Docker
* KIND
* kubectl
* Linux / WSL

## Create the Cluster

```bash
kind create cluster --name abi-cluster --config config.yml
```

## Verify the Cluster

```bash
kubectl get nodes
kubectl cluster-info
```

## Project Structure

```text
.
├── config.yml
├── manifests/
├── deployments/
└── README.md
```

## Learning Goals

* Understand Kubernetes architecture
* Work with Pods, Deployments, and Services
* Learn cluster networking
* Practice troubleshooting with kubectl
* Prepare for Kubernetes certifications such as KCNA and CKA

## Notes

This repository is part of my Kubernetes learning journey and will be updated as I explore more Kubernetes concepts.
