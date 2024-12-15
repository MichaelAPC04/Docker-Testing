# Python Containerisation, CI/CD Workflow

This repository demonstrates a CI/CD pipeline for a containerised Python application with GitHub, testing in a local environment and automating deployments through GitHub Actions. Its features are:
- Python containerisation
- Local environment testing
- CI/CD pipeline
- Kubernetes integration (to test and debug)

## Application Features
- **GitHub Actions Workflow**:
  - Automate building Docker images
  - Logs into Docker Hub securely via GitHub Secrets
  - Pushes the containerised application to DockerHub
- **Local Kubernetes Deployment**:
  - Test & debug the containerised application in a Kubernetes cluster

_Note that the title of this repo needs to be changed to lowercase to rerun and build properly_
