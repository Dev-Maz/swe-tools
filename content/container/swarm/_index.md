+++
title = "Docker Swarm"
type = "chapter"
+++

Docker Swarm is a container orchestration tool for clustering and scheduling Docker containers. With Swarm,
IT administrators and developers can establish and manage a cluster of Docker nodes as a single virtual system.

Docker Swarm lets developers join multiple physical or virtual machines into a cluster. These individual machines are
known as nodes or daemons.

Docker Swarm also lets admins and developers launch Docker containers, connect containers to multiple hosts, handle
each node's resources and improve application availability throughout a system.

Docker Engine, the layer between the operating system and container images, natively uses Swarm mode. Swarm mode
integrates the orchestration capabilities of Docker Swarm into Docker Engine 1.12 and subsequent releases.
Docker Swarm uses the standard Docker API to interface with other Docker tools, such as Docker Machine.

The Docker platform includes a variety of tools, services, content and automations that help developers build, ship and
run applications without configuring or managing the underlying development environment. With Docker, developers
can package and run applications in lightweight containers -- loosely isolated environments that enable an application
to run efficiently and seamlessly in many different conditions.

Docker Swarm abstracts host resources into a shared pool for Docker containers.

With Docker Swarm, containers can connect to multiple hosts. Each node in the cluster can then easily deploy and access
any containers within that swarm. Docker Swarm includes multiple worker nodes and at least one manager node to control
the cluster's activities and ensure its efficient operations.

Clustering is an important feature for container technology. It creates a cooperative group of systems that provide
redundancy, enabling Docker Swarm failover if one or more nodes experience an outage. A Docker Swarm cluster also
enables administrators and developers to add or subtract container iterations as computing demands change.
