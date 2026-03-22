# LAMP Stack & WordPress Deployment | Apache | MySQL | PHP | Docker

## Overview

This repository demonstrates hands-on implementation of a LAMP (Linux, Apache, MySQL, PHP) stack with WordPress deployment on Ubuntu. It also includes Apache performance tuning, security hardening, SSL configuration, and containerization using Docker.

The project showcases real-world system administration, web server configuration, and DevOps practices.

---

## Documentation

Detailed implementation steps, configurations, and outputs are available in:

* `/docs/lamp-stack-learning.pdf`
* `/docs/lamp-wordpress-setup.pdf`

---

## Core Skills Demonstrated

* Linux System Administration
* Web Server Configuration (Apache HTTP Server)
* Database Management (MySQL)
* Server-side Scripting (PHP)
* WordPress Deployment & Configuration
* Apache Performance Tuning & Optimization
* Security Hardening (ServerTokens, ServerSignature)
* SSL/TLS Configuration
* Containerization using Docker & Docker Compose

---

## Technical Implementation

### LAMP Stack Setup

* Installed and configured Apache, MySQL, and PHP on Ubuntu/CentOS
* Configured firewall rules (HTTP, HTTPS, SSH)
* Verified services using systemctl and service status checks 

### Apache Configuration & Optimization

* Modified Apache configuration files (`apache2.conf`, `httpd.conf`)
* Configured Multi-Processing Modules (MPM Prefork & Event)
* Enabled PHP-FPM for efficient request handling
* Tuned KeepAlive and worker settings for performance
* Implemented caching modules (cache, cache_disk)
* Performed benchmarking using Apache Bench (ab tool) with high request throughput 

### Security Hardening

* Configured ServerTokens and ServerSignature to reduce information exposure
* Implemented firewall rules and access control
* Generated self-signed SSL certificates for HTTPS communication 

### WordPress Deployment

* Installed WordPress on Apache web server
* Configured MySQL database and user for WordPress
* Set file permissions and ownership
* Configured Apache Virtual Host for WordPress
* Enabled rewrite module and site configuration 

### Database Configuration

* Created and managed MySQL databases and users
* Configured database connectivity for WordPress

### Containerization (Docker)

* Created Dockerfile for PHP application
* Configured Docker Compose for multi-service setup (Apache + PHP-FPM)
* Deployed PHP application using containers
* Exposed services via ports and verified application access 

---

## Key Achievements

* Successfully deployed a complete LAMP stack environment
* Configured and optimized Apache for high performance
* Deployed WordPress with proper database integration
* Implemented security best practices for web server
* Containerized PHP application using Docker and Docker Compose
* Conducted performance benchmarking and tuning

---

## Tools & Technologies

Linux | Apache | MySQL | PHP | WordPress | Docker | Docker Compose | SSL | Apache Bench

---

## Purpose

This project serves as a practical demonstration of deploying and managing web applications using LAMP architecture, along with performance tuning and containerization techniques used in real-world DevOps environments.

---

## Note

This repository focuses on practical implementation and real-time configurations rather than theoretical concepts.
