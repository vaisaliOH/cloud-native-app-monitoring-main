Project Requirements Document

Automated Cloud Infrastructure Monitoring Dashboard using Docker Compose and GitHub Actions

⸻

1. Project Overview

This project focuses on automated cloud-native deployment and monitoring of a lightweight web application using cloud technologies.

The main objective is to deploy a simple static website on an AWS EC2 cloud instance, containerize the services using Docker Compose, automate deployment using the GitHub Actions CI/CD pipeline, and continuously monitor the cloud server using Prometheus and Grafana.

The application itself is intentionally minimal, as the primary emphasis is on cloud deployment, automation, container orchestration, and monitoring.

⸻

2. Problem Statement

Traditional application deployment on cloud servers often involves manual configuration, deployment, and monitoring, which can be time-consuming and error-prone.

This project aims to automate the deployment lifecycle and provide real-time infrastructure monitoring using modern cloud-native tools.

⸻

3. Main Goals / Objectives

Primary Goals
	•	Deploy an application on a cloud server
	•	Automate deployment using CI/CD
	•	Use containerization for easy service management
	•	Monitor cloud server health in real time
	•	Demonstrate cloud-native deployment workflow

Specific Objectives
	•	Host a sample web application on AWS
	•	Use Docker Compose to manage multiple containers
	•	Use GitHub Actions for automated deployment on every code push
	•	Monitor CPU, memory, disk, and network usage
	•	Visualize metrics using dashboards

⸻

4. Scope of the Project

The scope includes:
	•	Cloud deployment on AWS EC2
	•	Containerized services
	•	Automated CI/CD pipeline
	•	Infrastructure monitoring dashboard
	•	Static sample website deployment

The project does not focus on application development and uses a simple boilerplate webpage.

⸻

5. Functional Requirements

Deployment
	•	The system shall deploy the application automatically on code push
	•	The system shall run all services using Docker Compose
	•	The system shall restart containers if deployment updates occur

Monitoring
	•	The system shall collect server metrics
	•	The system shall display metrics on a dashboard
	•	The system shall monitor:
	•	CPU usage
	•	Memory usage
	•	Disk usage
	•	Network traffic
	•	Container health

User Access
	•	User should be able to access:
	•	Web app
	•	Prometheus dashboard
	•	Grafana dashboard

⸻

6. Non-Functional Requirements
	•	High availability of deployed services
	•	Easy scalability
	•	Low deployment complexity
	•	Reusable deployment pipeline
	•	Maintainable container configuration

⸻

7. Tech Stack

Cloud Platform
	•	Amazon Web Services
	•	Amazon EC2

Containerization
	•	Docker
	•	Docker Compose

CI/CD
	•	GitHub Actions
	•	GitHub

Monitoring
	•	Prometheus
	•	Grafana
	•	Node Exporter

Web Server
	•	Nginx

Version Control
	•	Git

⸻

8. Modules of the Project

Module 1 – Web Application

A static HTML boilerplate webpage served through Nginx.

Module 2 – Container Orchestration

Docker Compose configuration for all services.

Module 3 – CI/CD Automation

GitHub Actions workflow for automatic deployment.

Module 4 – Monitoring Dashboard

Prometheus and Grafana setup for infrastructure monitoring.

⸻

9. Expected Output
	•	Successful deployment on cloud
	•	Running web application
	•	Automated deployment on Git push
	•	Live Grafana monitoring dashboard
	•	Prometheus metrics collection

⸻

10. Expected Deliverables
	•	Source code repository
	•	docker-compose.yml
	•	GitHub Actions workflow file
	•	Monitoring dashboard screenshots
	•	Project documentation
