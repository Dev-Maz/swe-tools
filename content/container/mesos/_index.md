+++
title = "Mesos"
type = "chapter"
+++

Apache Mesos is an open-source project to manage computer clusters. It was developed at the University of California,
Berkeley.

Mesos began as a research project in the UC Berkeley RAD Lab by then PhD students Benjamin Hindman, Andy Konwinski,
and Matei Zaharia, as well as professor Ion Stoica. The students started working on the project as part of a course taught
by David Culler. It was originally named Nexus but due to a conflict with another university's project, was renamed to
Mesos.

Mesos was first presented in 2009 (while still named Nexus) by Andy Konwinski at HotCloud '09 in a talk accompanying
the first paper published about the project. Later in 2011 it was presented in a more mature state in a talk by Zaharia at
the Usenix Symposium on Networked Systems Design and Implementation conference about the paper "Mesos: A Platform for
Fine-Grained Resource Sharing in the Data Center" by Benjamin Hindman, Andy Konwinski, Zaharia, Ali Ghodsi,
Anthony D. Joseph, Randy Katz, Scott Shenker, Ion Stoica.

On July 27, 2016, the Apache Software Foundation announced version 1. It added the ability to centrally supply Docker,
rkt and appc instances.

On April 5, 2021, it was voted to move Mesos to the Apache Attic, however the vote was cancelled two days later due
to increased interest.

Mesos uses Linux cgroups to provide isolation for CPU, memory, I/O and file system. Mesos is comparable to Google's Borg
scheduler, a platform used internally to manage and distribute Google's services.

Software startup Mesosphere, Inc. sells the Datacenter Operating System, a distributed operating system, based on 
Apache Mesos. In September 2015, Microsoft announced a commercial partnership with Mesosphere to build container 
scheduling and orchestration services for Microsoft Azure. In October 2015, Oracle announced support for Mesos through
Oracle Container Cloud Service.
