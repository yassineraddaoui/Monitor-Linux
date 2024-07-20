# Grafana, Prometheus, and Node Exporter Setup with Docker Compose

This repository contains a Docker Compose configuration for setting up Grafana, Prometheus, and Node Exporter.

## Overview

### Prometheus
Prometheus is an open-source systems monitoring and alerting toolkit. It is designed for reliability and scalability, making it ideal for recording real-time metrics in a time-series database and offering powerful querying capabilities.

### Node Exporter
Node Exporter is a Prometheus exporter for hardware and OS metrics exposed by *nix kernels. It allows Prometheus to scrape system-level metrics like CPU, memory, disk usage, and more from the host.

### Grafana
Grafana is an open-source platform for monitoring and observability. It allows you to query, visualize, alert on, and understand your metrics no matter where they are stored. Grafana provides a powerful and elegant way to create, explore, and share dashboards and data with your team.

![Dashboard Screenshot](./linux.png)

## Prerequisites

Make sure you have Docker and Docker Compose installed on your system.

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

