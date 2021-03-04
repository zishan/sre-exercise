# SRE Exercise
Build, Deploy and Monitor on Kubernetes

## Summary

The candidate should build a Docker image from a "hello world" web application, deploy it to a Kubernetes cluster and instrument monitoring.

## Setup
Some requirements are left intentionally vague:

  * There must be a "hello world" type web application in your personal Github account. The language doesn't matter, e.g. ruby, python, java, etc. You are welcome to use the following:
    * https://github.com/brentley/ecsdemo-frontend
    * https://github.com/brentley/ecsdemo-nodejs
    * https://github.com/brentley/ecsdemo-crystal
  * You may run a Docker registry and Kubernetes on your localhost (see Docker Desktop).
  * There must be Docker image(s) built from a Dockerfile in the application source code.
  * There must be Kubernetes deployment, service and ingress definitions used to start the application with reference to the aforementioned Docker image(s).
  * There must be Kubernetes monitoring instrumented using New Relic.

## Requirements
  * We must be able to view your application code, Dockerfile, Kubernetes manifests and New Relic instrumentation.
  * You must be able to deploy the application using kubectl commands
  * You must be able to view application deployment status using kubectl commands
  * You must be able to successfully load/display the application in a web browser
  * You must be able to view/display pod CPU and RAM usage in New Relic.

## Extra Credit
  * Host your Kubernetes cluster in AWS
  * Host your Docker image on dockerhub.com
  * Deploy your application with Helm
  * Deploy your infrastructure with Terraform
  * Install a Kubernetes Dashboard
  * Install New Relic APM in your application

## Double Extra Credit
  * Enable us to load your application in our browser
  * Enable us to view pod CPU and RAM usage in New Relic
  * CD pipeline that builds and deploys on every commit/push

## Submission
Once the exercise is completed, the candidate must do the following:

 * Add 'zishan' as a collaborator to your hello world repository
 * Email the following to zahmad(at)teladoc.com
   * Github url for the hello world repository
   * Public DNS name for the application instance (if applicable)

## Evaluation
After the candidate has provided their submission, we will then schedule a phone call to discuss the implementation in detail.

We want to see that the candidate can speak to implementation decisions and the reasoning behind them. Additionally, we're looking for familiarity with our chosen technology stack or the capacity to apply familiar concepts to unfamiliar technologies.
