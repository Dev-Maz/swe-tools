+++
title = "Kubernetes"
type = "chapter"
+++

Kubernetes is an open-source container orchestration system for automating software deployment, scaling, and management.
Originally designed by Google, the project is now maintained by a worldwide community of contributors, and the trademark
is held by the Cloud Native Computing Foundation.

The name Kubernetes originates from the Greek κυβερνήτης (kubernḗtēs), meaning 'governor', 'helmsman' or 'pilot'.
Kubernetes is often abbreviated as K8s, counting the eight letters between the K and the s (a numeronym).

Kubernetes assembles one or more computers, either virtual machines or bare metal, into a cluster which can run workloads
in containers. It works with various container runtimes, such as containerd and CRI-O. Its suitability for running
and managing workloads of all sizes and styles has led to its widespread adoption in clouds and data centers. There are
multiple distributions of this platform – from independent software vendors (ISVs) as well as hosted-on-cloud offerings
from all the major public cloud vendors.

Kubernetes is one of the most widely deployed software systems in the world being used across companies including Google,
Microsoft, Amazon, Apple, Meta, Nvidia, Reddit and Pinterest.

Kubernetes defines a set of building blocks ("primitives") that collectively provide mechanisms that deploy, maintain,
and scale applications based on CPU, memory or custom metrics. Kubernetes is loosely coupled and extensible to meet the
needs of different workloads. The internal components as well as extensions and containers that run on Kubernetes rely
on the Kubernetes API. The platform exerts its control over compute and storage resources by defining resources as objects,
which can then be managed as such.

Kubernetes follows the primary/replica architecture. The components of Kubernetes can be divided into those that manage
an individual node and those that are part of the control plane.
