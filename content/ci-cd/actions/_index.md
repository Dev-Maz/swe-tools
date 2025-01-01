+++
title = "Github Actions"
type = "chapter"
+++

GitHub Actions is a platform for continuous integration / continuous delivery (CI/CD). It enables you to automate build,
testing, and deployment pipelines. It also lets you run arbitrary code on a specified repository when an event occurs.
Actions uses code packages in Docker containers that run on GitHub servers. They are compatible with all programming
languages to ensure you can run them on public clouds as well as local servers.

GitHub Actions allows you to configure your workflow to be triggered once a specific event occurs in the repository.
For example, when an issue is created or when a pull request is opened. 

A workflow contains one or several jobs running in parallel or sequential order. Each job runs inside a container or in
a separate virtual machine (VM) runner. Additionally, each job includes one or several steps that run a predefined script
or an action, a reusable extension that simplifies your workflow.

A GitHub Actions workflow is an automated process that runs one or several jobs. You can configure workflows by defining
a YAML file, which is checked into the repository. This file runs when: 

- Triggered by a specific event in the repository

- Triggered manually

- At a predefined schedule

You can find workflow definitions in the .github/workflows directory of each repository. A repository can include several
workflows, each performing different tasks. You can use, for example, one workflow for building and testing pull requests,
another workflow for deploying the application whenever a release is created, and an additional workflow for adding
a label whenever a new issue is opened.

An event is a specific activity in a repository that triggers a workflow run. For example, activity can originate from
GitHub when someone creates a pull request, opens an issue, or pushes a commit to a repository. You can also trigger
a workflow run on a schedule, by posting to a REST API, or manually.
