# Runners

**Description:**

This Koan makes use of Runners, which enables you to use your own infrastructure for running jobs. This means you will be able to build and test on a wider variety of architectures, as well as have additional control over the environment.

What key aspects are important to note?

**Goals:**

- Carry out all pre-requisites to running tasks on a runner (authentication etc)
- Create your machine runner using the relevant option for your OS.
  - Make sure you use Machine runner 3, and **not** the legacy machine runner 1.
- Create your container runner.
  - [minikube](https://minikube.sigs.k8s.io/docs/start/?arch=%2Fmacos%2Fx86-64%2Fstable%2Fbinary+download) is a great option for running local container runners
- Edit the config to enable the jobs to run on your runners.
- Share Link to green job & image of agent running the job.

![runner](/18%20Runners/src/runner.png)

**Help:**

<details>
  <summary>Spoiler warning</summary>

https://circleci.com/docs/guides/execution-runner/machine-runner-3-configuration-reference/
https://circleci.com/docs/guides/execution-runner/install-machine-runner-3-on-macos/
https://circleci.com/docs/container-runner-installation/
https://circleci.com/docs/container-runner/

</details>
