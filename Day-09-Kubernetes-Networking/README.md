\# Day 9 – Kubernetes Networking \& Components



\## Overview



On Day 9, I learned about Kubernetes networking, the main

components involved in a Kubernetes cluster, and how user traffic

moves through the Kubernetes environment.



\---



\## Kubernetes Components



I learned about the important components that work together in

a Kubernetes cluster.



The main components include:



\- Control Plane

\- Worker Node

\- Pod

\- Service



These components work together to manage and provide access to

applications running in Kubernetes.



\---



\## Kubernetes Networking



Kubernetes networking allows different parts of the cluster to

communicate with each other.



It provides communication between:



\- Pods

\- Services

\- Worker Nodes

\- Users and applications



Networking is important because applications running inside

Kubernetes need to communicate with each other and receive

traffic from users.



\---



\## User Traffic



I learned about how user traffic can reach an application running

inside a Kubernetes cluster.



A simplified flow is:



```text

User

&#x20; ↓

Service

&#x20; ↓

Pod

&#x20; ↓

Application

