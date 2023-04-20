# Power Platform Automated Deployment with GitHub Actions (ALM)

## Environments used
- build
- dev
- hotfix
- prod

Each of the above environments have specific purposes that they will fulfill. 

### build
Used for performing build operations, importing unmanaged solutions, converting to managed solutions, integration validation.

### dev
Main develoment environment will development activities will take place, this can be a single dev environment or several that are used by different developers.

### hotfix
This is used for working on hotfixes and keeping current work items isolated from hotfix work. This provides a way of separating from a regular iterations work items to resolve issue(s) that need to be worked on and released outside of a normal iteration.

### test
Test environment used for user acceptance testing.

### prod
Production envrionment, only publish managed solutions and used for production access to the system.

## GitHub Workflows

### build-deploy-solution.yml

### convert-unmanaged-to-managed.yml

### delete-and-import-unmanaged-solution.yml

### delete-unmanaged-solution-and-components-from-environment.yml

### deploy-tagged-solution-to-environment.yml

### determine-solution-build-deploy.yml

### export-unpack-commit-solution.yml

### import-unmanaged-solution.yml

### workflows-pr.yml





## Solution



