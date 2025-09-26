# Enterprise Airflow with Docker

This repository demonstrates how to set up and run **Apache Airflow** in a containerized environment using **Docker** and **Docker Compose**, designed with enterprise-grade applications in mind.  

The setup includes:
- **Airflow Webserver, Scheduler, Worker, and Triggerer**
- **PostgreSQL** as the metadata database
- **Redis** as the message broker
- **Docker Compose orchestration**
- Example **DAGs** for workflow automation

---

## Overview

Apache Airflow is a powerful open-source platform to programmatically author, schedule, and monitor workflows.  
This repository provides a **step-by-step installation guide** with screenshots to help you quickly deploy Airflow locally and adapt it for **enterprise applications** such as:

- Data Engineering Pipelines  
- ETL / ELT Workflows  
- IoT & Sensor Data Processing  
- Machine Learning Model Training & Deployment  
- Enterprise Task Automation  

---

## Repository Structure

enterprise-airflow-docker-setup/
│── dags/                  # Example DAGs
│── docker-compose.yaml    # Airflow + Postgres + Redis setup
│── logs/                  # Airflow logs
│── plugins/               # Custom plugins (if any)
│── docs/screenshots/      # Installation screenshots
│── README.md              # Project documentation



##  Installation

1. Clone the repository
   
   ```bash
   git clone https://github.com/your-username/enterprise-airflow-docker-setup.git
   cd enterprise-airflow-docker-setup

2. Start Airflow with Docker Compose
   
   ```ruby
   docker-compose up -d
   ```

3. Access the Airflow Web UI at:
   
 ```ruby
   http://127.0.0.1:8080
 ```



