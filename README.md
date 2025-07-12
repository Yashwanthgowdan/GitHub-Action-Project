##Flask App CI/CD Pipeline with GitHub Actions

Objective
This project demonstrates how to implement a CI/CD workflow using GitHub Actions for a Python-based Flask web application. The pipeline automatically installs dependencies, runs tests, builds the application, and deploys it to staging or production environments.

Repository Setup
Main branch: main — represents the production-ready code.
Staging branch: staging — used to test features in a staging environment before going to production.

GitHub Actions Workflow
The CI/CD workflow is defined in the file:
.github/workflows/main.yml

Triggered on:
Push to staging: Triggers full pipeline and deploys to staging.

Environment Secrets:
To enable deployments, add the following secrets to your repository in Settings → Secrets → Actions:

EC2_IP
EC2_NAME
EC2_SSH
<img width="1365" height="394" alt="image" src="https://github.com/user-attachments/assets/2b24b476-d5f2-4777-8671-391313eeb02b" />
