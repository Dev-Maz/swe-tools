+++
title = "Docker"
type = "chapter"
+++

Docker is a set of platform as a service (PaaS) products that use OS-level virtualization to deliver software in packages
called containers. The service has both free and premium tiers. The software that hosts the containers is called
Docker Engine. It was first released in 2013 and is developed by Docker, Inc.

Docker is a tool that is used to automate the deployment of applications in lightweight containers so that applications
can work efficiently in different environments in isolation.

Containers are isolated from one another and bundle their own software, libraries and configuration files; they can
communicate with each other through well-defined channels. Because all of the containers share the services of a single
operating system kernel, they use fewer resources than virtual machines.

Docker can package an application and its dependencies in a virtual container that can run on any Linux, Windows, or macOS
computer. This enables the application to run in a variety of locations, such as on-premises, in public (see decentralized
computing, distributed computing, and cloud computing) or private cloud. When running on Linux, Docker uses the resource
isolation features of the Linux kernel (such as cgroups and kernel namespaces) and a union-capable file system
(such as OverlayFS) to allow containers to run within a single Linux instance, avoiding the overhead of starting
and maintaining virtual machines. Docker on macOS uses a Linux virtual machine to run the containers.

Because Docker containers are lightweight, a single server or virtual machine can run several containers simultaneously.
A 2018 analysis found that a typical Docker use case involves running eight containers per host, and that a quarter
of analyzed organizations run 18 or more per host. It can also be installed on a single board computer like the
Raspberry Pi.

The Linux kernel's support for namespaces mostly isolates an application's view of the operating environment, including
process trees, network, user IDs and mounted file systems, while the kernel's cgroups provide resource limiting
for memory and CPU. Since version 0.9, Docker includes its own component (called libcontainer) to use virtualization
facilities provided directly by the Linux kernel, in addition to using abstracted virtualization interfaces via libvirt,
LXC and systemd-nspawn.

Docker implements a high-level API to provide lightweight containers that run processes in isolation.
