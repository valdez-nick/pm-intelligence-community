# GitHub Actions Workflows

This directory contains automated CI/CD workflows for the PM Intelligence Platform.

## Workflows

### ci.yml
Main CI/CD pipeline that runs on every push and pull request:
- Linting and code formatting checks
- Type checking
- Unit and integration tests
- Security scanning
- Package building and publishing (on main branch)

## Required Secrets

The following secrets need to be configured in the repository settings:

- `PYPI_API_TOKEN`: PyPI API token for publishing Python packages
