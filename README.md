# Movie Picture Pipeline

You've been brought on as the DevOps resource for a development team that manages a web application that is a catalog of Movie Picture movies. They're in dire need of automating their development workflows in hopes of accelerating their release cycle. They'd like to use Github Actions to automate testing, building and deploying their applications to an existing Kubernetes cluster.

The team's project is comprised of 2 application.

1. A frontend UI built written in Typescript, using the React framework
2. A backend API written in Python using the Flask framework.

In the `starter` folder, you'll find 2 folders, one named `frontend` and one named `backend`, where each application's source code is maintained. Your job is to use the team's [existing documentation](./starter/frontend/frontend-development-notes) and create CI/CD pipelines to meet the teams' needs.

## Deliverables

### Github link
https://github.com/nhutth221200/udacity-project-4

### workflows
1. ./github/workflows/frontend-ci.yaml
A Continuous Integration workflow of frontend that run linting, tests and build jobs

2. ./github/workflows/frontend-cd.yaml
A Continuous Deployment workflow that run linting, and deploying of the application

3. ./github/workflows/backend-ci.yaml
A Continuous Integration workflow of backend that run linting, tests and build jobs

4. ./github/workflows/backend-cd.yaml
A Continuous Deployment workflow that run linting, and deploying of the backend

## License

[License](LICENSE.md)
