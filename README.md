# Initial CI/CD

This repository demonstrates a basic Continuous Integration and Continuous Deployment (CI/CD) pipeline using **GitHub Actions** and a **Linux server**.

## Features

- Automated workflow with GitHub Actions
- Continuous Integration for code validation
- Continuous Deployment to a Linux server
- Automatic deployment on repository updates
- Simple and easy-to-understand CI/CD setup

## Tech Stack

- GitHub Actions
- Linux Server
- Git
- SSH
- Docker

## Workflow

1. Pushed changes to the GitHub repository.
2. GitHub Actions automatically triggers the workflow.
3. The workflow connects securely to the Linux server using SSH.
4. The latest code is deployed to the server automatically.

## Repository Structure

```
.github/
└── workflows/
    └── deploy.yml
```

## Purpose

This project was created to demonstrate how a basic CI/CD pipeline can automate the deployment process, reducing manual work and ensuring consistent deployments.

## License

This project is intended for educational purposes.
