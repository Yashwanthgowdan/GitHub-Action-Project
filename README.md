# Flask App with CI/CD Pipeline

This project is a simple Flask application integrated with a **CI/CD pipeline** using **GitHub Actions** and **AWS EC2** for deployment.

Tech Stack
Python 3.11
Flask
Pytest(for unit testing)
GitHub Actions(CI/CD)
AWS EC2 for Deployment)

Features
- Automatically installs dependencies on code push.
- Runs unit tests using `pytest`.
- Deploys to **Staging EC2** on `staging` branch push.
- Deploys to **Production EC2** on release tag push (`v*.*.*`).
- Secure SSH-based deployment using GitHub Secrets.
