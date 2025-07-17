# TerraHarbor

*A safe harbor for your Terraform/OpenTofu state files*

## Overview

TerraHarbor project is a Terraform/OpenTofu HTTP backend designed to provide a secure and efficient way to store and manage Terraform/OpenTofu state files. It aims to be a simple and effective solution for teams and organizations looking to centralize their Terraform/OpenTofu state management.

> [!NOTE]
> This project is being developed as a school project for the PDG course at [HEIG-VD](https://www.heig-vd.ch/).

## Authors

- Anthony Christen ([@Anthony-Christen](https://github.com/Anthony-Christen))
- Badis Machraoui (TODO)
- Fabrice Chapuis ([@fabricechapuis](https://github.com/fabricechapuis))
- Gonçalo Carvalheiro Heleno ([@lentidas](https://github.com/lentidas))
- Sven Ferreira Silva ([@Svelva](https://github.com/Svelva))

## Repositories

This organization contains several repositories in order to more efficiently manage the project and its components. Here is a list of the main repositories along with their purpose:

- [terraharbor/.github](https://github.com/terraharbor/.github) - *this repository*;
- [terraharbor/project-management](https://github.com/terraharbor/project-management) - general documentation for the project (p.e. contributing guidelines) and store for the generic GitHub Issues we are using to manage the project (e.g. epics, user stories, etc.);
- [terraharbor/github-org-management](https://github.com/terraharbor/github-org-management) - Terraform code and GitHub Actions workflows to manage the repositories, teams and members of the TerraHarbor organization;
- [terraharbor/github-actions-workflows](https://github.com/terraharbor/github-actions-workflows) - centralized repository for GitHub Actions workflows used by the other repositories in the TerraHarbor organization; additionally, it contains the GitHub Actions workflow that runs Renovate periodically to update the dependencies of the repositories in the organization;
- [terraharbor/application](https://github.com/terraharbor/application) - main application repository for the TerraHarbor project, containing the core functionality and components;
- [terraharbor/infrastructure](https://github.com/terraharbor/infrastructure) - repository for the infrastructure code, to deploy the TerraHarbor application a Kubernetes cluster;
- [terraharbor/website](https://github.com/terraharbor/website) - repository for the TerraHarbor project website.
