# Jenkins CI/CD Configuration

## Overview
Jenkins was configured on the AWS master EC2 instance to automate application build, testing and production deployment.

## Jenkins Jobs

### Job 1 – Build
- Configured to retrieve source code from GitHub.
- Configured with the develop branch.
- Used to build the application and prepare the Docker image.

### Job 2 – Test
- Configured as part of the application testing workflow.
- Used to verify the application on the test environment.

### Job 3 – Production
- Configured for the production deployment workflow.
- Used to deploy the application to the production environment.

## GitHub Integration
- Configured a GitHub webhook.
- Enabled automatic Jenkins build triggers.
- Used master and develop branches.

## Tools Used
- Jenkins
- GitHub
- Docker
- AWS EC2
- Ansible
