# GitLab-CI

In today's challenge, we are going to learn how Continuous Integration can be achieved when working with Gitlab in your projects.

#### Learning Objectives:

Gitlab-CI structure and synthax
Gitlab Container Registry
Gitlab Runner

### The mission
As a DevOps engineer working at ACME a consulting compagny that helps their clients to optimize their software development process. You a currently working on two different projects (Project 1 / Project 2) for which you will have to implement a CI/CD pipeline in Gitlab. Make sure that the application build process (build/test/release/deploy) can be done each time a developer makes a commit on the main branch. Also, each project has to be containerized (which is not the case for now).

For the release step, you will have to push your docker image to Gitlab's Container Registry.

Quick note
- Use you VM to install your Gitlab Runner.

- Deployement has to be done one your VM.

- Use gitlab.com and not a self hosted version of gitlab.

#### Useful links
https://docs.gitlab.com/ee/ci/introduction/index.html#continuous-integration 

https://docs.gitlab.com/runner/ - Gitlab runner

https://www.youtube.com/watch?v=-CyVpfDQAG0 - explanation about gitlab runner (how to install and register runner)
