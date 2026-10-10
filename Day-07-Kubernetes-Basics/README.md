\# Day 7 – Kubernetes Basics



\## Overview



On Day 7, I was introduced to Kubernetes and its basic

architecture.



I also downloaded/installed Kubernetes and learned about the

main components of a Kubernetes cluster.



\---



\## What is Kubernetes?



Kubernetes is a platform used to manage containerized

applications.



It helps in deploying and managing containers in a cluster.



\---



\## Kubernetes Cluster



A Kubernetes cluster consists mainly of:



\- Master Node / Control Plane

\- Worker Node



These components work together to manage and run

containerized applications.



\---



\## Master Node / Control Plane



The Master Node, also called the Control Plane, is responsible

for managing the Kubernetes cluster.



It controls and manages the worker nodes and the applications

running in the cluster.



\---



\## Worker Node



A Worker Node is the machine where the application workloads

and containers run.



Worker nodes receive instructions from the Control Plane and

run the required workloads.



\---



\## Basic Kubernetes Architecture



```text

&#x20;                Kubernetes Cluster

&#x20;                       │

&#x20;               ┌───────▼────────┐

&#x20;               │  Master Node /  │

&#x20;               │  Control Plane  │

&#x20;               └───────┬────────┘

&#x20;                       │

&#x20;            ┌──────────┴──────────┐

&#x20;            │                     │

&#x20;     ┌──────▼──────┐       ┌──────▼──────┐

&#x20;     │ Worker Node │       │ Worker Node │

&#x20;     │             │       │             │

&#x20;     │ Applications│       │ Applications│

&#x20;     │ Containers  │       │ Containers  │

&#x20;     └─────────────┘       └─────────────┘

