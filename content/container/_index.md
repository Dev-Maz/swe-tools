+++
title = "Containerization"
type = "chapter"
+++

In software engineering, containerization is operating-system–level virtualization or application-level virtualization
over multiple network resources so that software applications can run in isolated user spaces called containers
in any cloud or non-cloud environment, regardless of type or vendor. The term "container" is overloaded, and it is
important to ensure that the intended definition aligns with the audience's understanding.

Each container is basically a fully functional and portable cloud or non-cloud computing environment surrounding
the application and keeping it independent of other environments running in parallel. Individually, each container simulates
a different software application and runs isolated processes by bundling related configuration files, libraries
and dependencies. But, collectively, multiple containers share a common operating system kernel (OS).

In recent times, containerization technology has been widely adopted by cloud computing platforms like Amazon Web Services,
Microsoft Azure, Google Cloud Platform, and IBM Cloud. Containerization has also been pursued by the U.S. Department
of Defense as a way of more rapidly developing and fielding software updates, with first application in its F-22 air
superiority fighter.

Container orchestration or container management is mostly used in the context of application containers. Implementations
providing such orchestration include Kubernetes and Docker swarm.

Container clusters need to be managed. This includes functionality to create a cluster, to upgrade the software or repair
it, balance the load between existing instances, scale by starting or stopping instances to adapt to the number of users,
to log activities and monitor produced logs or the application itself by querying sensors. Open-source implementations of 
such software include OKD and Rancher. Quite a number of companies provide container cluster management as a managed
service, like Alibaba, Amazon, Google, Microsoft.
