# SBOM Analysis platform - Dependency-Track Setup with PostgreSQL Database and NGINX Reverse Proxy for TLS

# Overview
This repository provides a streamlined setup for Dependency-Track, a Component Analysis (CA) platform designed to identify and mitigate risks in your software supply chain. The setup includes configurations for using a PostgreSQL database for storage and NGINX as a reverse proxy to handle TLS termination for secure communication.

# Features
PostgreSQL Database: A robust and scalable database solution to store Dependency-Track data.
NGINX Reverse Proxy: Efficiently handles TLS termination, enabling secure communication over HTTPS.
Docker Compose: Simplifies deployment and management of the entire Dependency-Track environment.

# Prerequisites
Make sure you have the following installed on your system:
Docker
Docker Compose
PostgreSQL
NGINX
Usage
Clone this repository to your local environment:


`git clone https://github.com/vrkaushik/Dependency-Track.git`


Use Docker Compose to deploy Dependency-Track, PostgreSQL, and NGINX:

`docker-compose up -d`

Access Dependency-Track securely via your preferred web browser

