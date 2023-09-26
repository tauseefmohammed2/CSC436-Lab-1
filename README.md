# Web Applications: Lab 1 Repository

This repository contains the the personal biography page and the set of solved JavaScript exercises.

## Features

- **CI/CD Pipeline**: Automated using GitHub Actions.
- **Code Style & Linting**: Formatting ensured using Prettier.
- **Testing**: Validating the JavaScript Exercises using Jest(Using the Supplied Test Cases).
- **Deployment**: Automated deployment to AWS S3.

## CI/CD Pipeline Overview

1. **Checkout**: Clones the repository.
2. **Setup Node.js**: Initializes a Node.js environment.
3. **Install Dependencies**: Installs npm packages.
4. **Run Prettier**: Formats the code.
5. **Run Tests**: Executes test cases.
6. **Semantic Release**: Handles versioning.
7. **Deployment**: Deploys to an AWS S3 bucket.

### AWS S3 Deployment

Deployment is handled through GitHub Actions. The repository's contents are synced to the specified AWS S3 bucket in my AWS Account. All the required AWS credentials are securely stored in GitHub Secrets.