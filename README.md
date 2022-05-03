# Quizzler

## Description

The goal of this project is to demonstrate my understand and experience  working with the following technologies

- Docker
- Kubernetes
- Git
- CI/CD: CircleCI
- GitOps: ArgoCD
- Monitoring - Prometheus/Grafanna
- Logging: ELK stack
- Deployment - AWS


This project named **Quizzler** is small react project that allow users to take quizzes.


The aim of this project is to demonstrate my understanding of DevOps operational skills

### Requirements of Quizzler

- Quizzler should be deployable in different data centers exposed to the internet with different URLs

- The deployment should be packaged in such a way so that is fully compatible with a modern CI/CD tool e.g. ArgoCD, Flux, GitLab, Jenkins, Harness, Spinnaker

- During deployment, the user should experience zero downtime

- The deployment should have the ability to rollback if needed

- There should be an automated recovery in case of failure

#### Environment

- Node 12+

#### How to run

- first run `npm i` to install all dependencies
- Then run `npm run start` to start the project.

#### How to test

- Run `npm run test` to start the test runner

