# Eigen Prime 0 Software Development Workflow

Welcome to the Eigen Prime 0 software development workflow! This document outlines the guidelines and procedures to ensure efficient collaboration and code quality within the Eigen Prime 0 repository.

## Branching Strategy

We follow the **Git Flow** branching model for managing branches within the repository:

- **main:** The main branch represents the stable production-ready version of the software. It should always contain deployable code.
- **develop:** The develop branch serves as the integration branch for ongoing development efforts. Feature branches are merged into this branch for testing and integration.
- **Feature branches:** Feature branches are created from the develop branch for implementing new features or making changes. Once development is complete, they are merged back into the development branch via pull requests.
- **Hotfix branches:** Hotfix branches are created from the main branch to address critical issues or bugs in the production code. Once fixes are applied, they are merged into both main and developed branches.

## Pull Request Workflow

When contributing to Eigen Prime 0, follow these steps for submitting pull requests:

1. **Create a Feature Branch:**
   - Create a new feature branch from the develop branch using the following naming convention: `feature/<feature-name>`.

2. **Implement Changes:**
   - Implement your changes or new features in the feature branch, following the project's coding standards and guidelines.

3. **Submit Pull Request:**
   - Once your changes are ready, submit a pull request (PR) to merge your feature branch into the develop branch.
   - Provide a descriptive title and detailed description of the changes in the PR.

4. **Code Review:**
   - Other team members will review your code, providing feedback and suggestions for improvement.
   - Address any feedback or comments raised during the code review process.

5. **Merge Pull Request:**
   - Once the PR is approved and all discussions are resolved, it can be merged into the development branch.

## Continuous Integration/Continuous Deployment (CI/CD)

We use CI/CD pipelines to automate the testing and deployment process:

- **Continuous Integration (CI):** Automatically runs tests and checks code quality whenever changes are pushed to feature branches or pull requests.
- **Continuous Deployment (CD):** Automates the deployment of the application to staging or production environments after passing all tests.

## Versioning

We use [Semantic Versioning (SemVer)](https://semver.org/) for versioning releases:

- Given a version number MAJOR.MINOR.PATCH, increment the:
  - MAJOR version when making incompatible API changes,
  - MINOR version when adding functionality in a backwards-compatible manner, and
  - PATCH version when making backward-compatible bug fixes.

## Feedback and Contribution

We welcome contributions from the community to help improve Eigen Prime 0. Feel free to open issues for bug reports, feature requests, or suggestions for improvement. Pull requests are also encouraged and appreciated!

Thank you for being a part of the Eigen Prime 0 development community!

