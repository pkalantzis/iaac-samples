# Infrastructure-as-a-Code (IaaC) Resources Collection

> A curated list of Docker Compose and other samples.

These samples provide a starting point for how to integrate different services using a Compose file and to manage their deployment with Docker Compose, and other methods.

> **Note**
> The following samples are intended for use in local development environments such as project setups, tinkering with software stacks, etc. These samples must not be deployed in production environments.

<!-- lint disable awesome-toc -->
## Contents
<!-- - [Docker Compose Information Security & Privacy related services samples](#docker-compose-information-security--privacy-related-services-samples) -->
- [Docker Compose multiple integrated services samples](#docker-compose-multiple-integrated-services-samples)
- [Docker Compose single service samples](#docker-compose-single-service-samples)
- [Other interesting useful stuff](#other-interesting-useful-stuff)
<!--
## Docker Compose Information Security &amp; Privacy related services samples
-->

## Docker Compose multiple integrated services samples
- [`Wordpress / MySQL`](docker-compose/wordpress-mysql/compose.yml) - Sample Wordpress and MySQL stack

## Docker Compose single service samples
- [`MariaDB`](docker-compose/mariadb/compose.yml) - Sample MariaDB instance with phpMyAdmin support
- [`MySQL`](docker-compose/mysql/compose.yml) - Sample MySQL instance with phpMyAdmin support
- [`PostgreSQL`](docker-compose/postgresql/compose.yml) - Sample PostgreSQL instance with pgAdmin support

## Other interesting useful stuff
<!--
- [`phpMyAdmin`](docker-compose/phpmyadmin/compose.yml) - Sample phpMyAdmin instance
-->
- [`Portainer`](docker-compose/portainer/compose.yml) - Sample Portainer instance
- [`Prometheus / Grafana`](docker-compose/prometheus-grafana/compose.yml) - Sample Prometheus and Grafana monitoring stack