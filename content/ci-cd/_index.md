+++
title = "CI/CD"
type = "chapter"
+++

In software engineering, CI/CD or CICD is the combined practices of continuous integration (CI) and continuous delivery (CD)
or, less often, continuous deployment. They are sometimes referred to collectively as continuous development or continuous
software development.

**Continuous integration**
:   Frequent merging of several small changes into a main branch.

**Continuous delivery**
:   Producing software in short cycles with high speed and frequency so that reliable software can be released at any time,
with a simple and repeatable deployment process when deciding to deploy.

**Continuous deployment**
:   Automatic rollout of new software functionality.

CI/CD bridges the gaps between development and operation activities and teams by enforcing automation in building,
testing and deployment of applications. CI/CD services compile the incremental code changes made by developers, then link 
and package them into software deliverables. Automated tests verify the software functionality, and automated deployment
services deliver them to end users. The aim is to increase early defect discovery, increase productivity, and provide
faster release cycles. The process contrasts with traditional methods where a collection of software updates were
integrated into one large batch before deploying the newer version.

Modern-day DevOps practices involve:

- continuous development,

- continuous testing,

- continuous integration,

- continuous deployment, and

- continuous monitoring

The CI/CD practice, or CI/CD pipeline, forms the backbone of modern day DevOps operations.

The following practices can enhance productivity of CI/CD pipelines, especially in systems hosted in the cloud:

- Number of Pipelines: Small teams can be more productive by having one repository and one pipeline. In contrast, larger organizations may have separate repositories and pipelines for each team or even separate repositories and pipelines for each service within a team.

- Permissions: In the context of pipeline-related permissions, adhering to the principle of least privilege can be challenging due to the dynamic nature of architecture. Administrators may opt for more permissive permissions while implementing compensating security controls to minimize the blast radius.
