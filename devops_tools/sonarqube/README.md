# SonarQube Community stacks

## Stack V1

The stack V1 use the following files:

* ```compose.v1.yml``` contains database and sonarqube containers for local environments
* ```.env.sonar.v1``` contains env variables to config containers in stack V1

## SonarCLI

In the ```compose.sonarcli.yml``` join with ```.env.sonarcli``` allow us to run sonarcli in local environments

## Pre-requirements:

* sysctl -w vm.max_map_count=524288
* sysctl -w fs.file-max=131072
* ulimit -n 131072
* ulimit -u 8192

Default user/pass: admin/admin

## Referencies:

- https://docs.sonarqube.org/latest/requirements/prerequisites-and-overview/
- https://github.com/OdesWiki/Instalar-SonarQube-en-Docker