# Advanced CI/CD Demo

This repository demonstrates an advanced GitHub Actions CI/CD pipeline.

## Workflow Stages
1. **Build** - Installs dependencies and builds the project.
2. **Test** - Runs tests on the built application.
3. **Deploy** - Deploys the app to a server (simulated).

## Secrets Required
- `PROD_DEPLOY_KEY` (SSH private key for deployment)

## Usage
Push changes to the main branch to trigger the workflow.
