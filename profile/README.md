<p align="center" style="margin-bottom: 0px !important;">
  <img width="128" src="logo.png" alt="TerraHarbor Logo" align="center">
</p>
<h1 align="center" style="margin-top: 0px;">TerraHarbor</h1>

<p align="center">A safe harbor for your Terraform state files</p>

<div align="center">

![Backend Version](https://img.shields.io/github/v/release/terraharbor/backend?style=for-the-badge&label=Backend%20Version) ![Backend License](https://img.shields.io/github/license/terraharbor/backend?style=for-the-badge&logo=gplv3&label=Backend%20License) ![Backend Build](https://img.shields.io/github/actions/workflow/status/terraharbor/backend/docker-build.yaml?branch=main&style=for-the-badge&logo=docker&label=Backend%20Build)

![Frontend Version](https://img.shields.io/github/v/release/terraharbor/frontend?style=for-the-badge&label=Frontend%20Version) ![Frontend License](https://img.shields.io/github/license/terraharbor/frontend?style=for-the-badge&logo=gplv3&label=Frontend%20License) ![Frontend Build](https://img.shields.io/github/actions/workflow/status/terraharbor/frontend/docker-build.yaml?branch=main&style=for-the-badge&logo=docker&label=Frontend%20Build)

</div>

## Overview

TerraHarbor project is a Terraform HTTP backend designed to provide a secure and efficient way to store and manage Terraform state files. It aims to be a simple and effective solution for teams and organizations looking to centralize their Terraform state management.

> [!NOTE]
> This project is being developed as a school project for the PDG course at [HEIG-VD](https://www.heig-vd.ch/).

## Authors

- Anthony Christen ([@Anthony-Christen](https://github.com/Anthony-Christen))
- Badis Machraoui ([@badisnt](https://github.com/badisnt))
- Fabrice Chapuis ([@fabricechapuis](https://github.com/fabricechapuis))
- Gonçalo Carvalheiro Heleno ([@lentidas](https://github.com/lentidas))
- Sven Ferreira Silva ([@Svelva](https://github.com/Svelva))

## Repositories

This organization contains several repositories in order to more efficiently manage the project and its components. Here is a list of the main repositories along with their purpose:

- [terraharbor/.github](https://github.com/terraharbor/.github) - *this repository*;
- [terraharbor/project-management](https://github.com/terraharbor/project-management) - general documentation for the project (p.e. contributing guidelines) and store for the generic GitHub Issues we are using to manage the project (e.g. epics, user stories, etc.);
- [terraharbor/github-org-management](https://github.com/terraharbor/github-org-management) - Terraform code and GitHub Actions workflows to manage the repositories, teams and members of the TerraHarbor organization;
- [terraharbor/github-actions-workflows](https://github.com/terraharbor/github-actions-workflows) - centralized repository for GitHub Actions workflows used by the other repositories in the TerraHarbor organization; additionally, it contains the GitHub Actions workflow that runs Renovate periodically to update the dependencies of the repositories in the organization;
- [terraharbor/backend](https://github.com/terraharbor/backend) - repository containing the code for the backend of the application, together with the database initialization scripts;
- [terraharbor/frontend](https://github.com/terraharbor/frontend) - repository containing the code for the frontend of the application;
- [terraharbor/infrastructure](https://github.com/terraharbor/infrastructure) - repository for the infrastructure code, to deploy the TerraHarbor application and its components;
- [terraharbor/website](https://github.com/terraharbor/website) - repository for the TerraHarbor project website.

## Getting Started

If you're a developer or contributor, a good place to start is the [terraharbor/project-management](https://github.com/terraharbor/project-management) repository, where you can find general documentation and guidelines for contributing to the project.

If you're a user interested in testing our application, you can [start by deploying it locally using Docker Compose](https://github.com/terraharbor/infrastructure?tab=readme-ov-file#running-docker-compose-locally).
