+++
title = "Argo CD"
type = "chapter"
+++

Argo CD is a Kubernetes-native continuous deployment (CD) tool. Unlike external CD tools that only enable push-based
deployments, Argo CD can pull updated code from Git repositories and deploy it directly to Kubernetes resources.
It enables developers to manage both infrastructure configuration and application updates in one system.

Argo CD offers the following key features and capabilities:

- Manual or automatic deployment of applications to a Kubernetes cluster.

- Automatic synchronization of application state to the current version of declarative configuration.

- Web user interface and command-line interface (CLI).

- Ability to visualize deployment issues, detect and remediate configuration drift.

- Role-based access control (RBAC) enabling multi-cluster management.

- Single sign-on (SSO) with providers such as GitLab, GitHub, Microsoft, OAuth2, OIDC, LinkedIn, LDAP, and SAML 2.0

- Support for webhooks triggering actions in GitLab, GitHub, and BitBucket.

GitOps is a software engineering practice that uses a Git repository as its single source of truth. Teams commit
declarative configurations into Git, and these configurations are used to create environments needed for the continuous 
delivery process. There is no manual setup of environments and no use of standalone scripts—everything is defined through
the Git repository.

A basic part of the GitOps process is a pull request. New versions of a configuration are introduced via pull request,
merged with the main branch in the Git repository, and then the new version is automatically deployed. The Git repository
contains a full record of all changes, including all details of the environment at every stage of the process.

Argo CD handles the latter stages of the GitOps process, ensuring that new configurations are correctly deployed
to a Kubernetes cluster. 
