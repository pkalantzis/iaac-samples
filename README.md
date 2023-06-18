# Infrastructure-as-a-Code (IaaC) Resources Collection

## Introduction

> A curated list of Docker Compose, Kubernetes and other Infrastructure as a Code (IaaC) samples.

These samples provide a starting point for how to integrate different services using a Compose file and to manage their deployment with Docker Compose, and other methods.

> **Note**
> The following samples are intended for use in local development environments such as project setups, tinkering with software stacks, etc. These samples must not be deployed in production environments.

<!-- lint disable awesome-toc -->
## Contents
* [Introduction](#introduction)
* [Docker Compose Samples](#docker-compose-samples)
  * [Information Security & Privacy related services](#information-security--privacy-related-services)
  * [Multiple integrated services](#multiple-integrated-services)
  * [Single services](#single-services)
  * [Other interesting useful stuff](#other-interesting-useful-stuff)
* [Kubernetes Samples](#kubernetes-samples)


## Docker Compose Samples

### Information Security &amp; Privacy related services
* [`Gitlab CE`](docker-compose/gitlab-ce/compose.yml) - Sample Gitlab Community Eddition Continuous Integration and Continuous Delivery (CI/CD) stack
* [`Prometheus / Grafana`](docker-compose/prometheus-grafana/compose.yml) - Sample Prometheus and Grafana monitoring stack
* [`Sonarqube CE`](docker-compose/sonarqube/compose.yml) - Sample Sonarcube Community Eddition Static Application Security Testing (SAST) stack

### Multiple integrated services
* [`Wordpress / MariaDB`](docker-compose/wordpress-mariadb/compose.yml) - Sample Wordpress and MariaDB stack
* [`Wordpress / MySQL`](docker-compose/wordpress-mysql/compose.yml) - Sample Wordpress and MySQL stack

### Single services
* [`Apache`](docker-compose/apache/compose.yml) - Sample Apache Web Server instance
* [`MariaDB`](docker-compose/mariadb/compose.yml) - Sample MariaDB database instance with phpMyAdmin support
* [`MySQL`](docker-compose/mysql/compose.yml) - Sample MySQL database instance with phpMyAdmin support
* [`PostgreSQL`](docker-compose/postgresql/compose.yml) - Sample PostgreSQL database instance with pgAdmin support
* [`Redis`](docker-compose/redis/compose.yml) - Sample Redis Cache instance

### Other interesting useful stuff
* [`Portainer`](docker-compose/portainer/compose.yml) - Sample Portainer instance
* [`phpMyAdmin`](docker-compose/phpmyadmin/compose.yml) - Sample phpMyAdmin instance
* [`pgAdmin`](docker-compose/pgadmin/compose.yml) - Sample pgAdmin instance

## Kubernetes Samples

* TBD