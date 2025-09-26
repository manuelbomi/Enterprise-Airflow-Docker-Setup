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

   
```ruby
enterprise-airflow-docker-setup/
│── dags/                  # Example DAGs
│── docker-compose.yaml    # Airflow + Postgres + Redis setup
│── logs/                  # Airflow logs
│── plugins/               # Custom plugins (if any)
│── docs/screenshots/      # Installation screenshots
│── README.md              # Project documentation

```

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
---

## Installation Walkthrough  📷

In a case of the reader preferring to do the Docker installation from ground up, this repository also includes step-by-step installation screenshots that shows installation details and commands used for all the keypoints,listed below:

* Docker Compose configuration (docker-compose.yaml)

* Starting containers (docker ps)

* Accessing the Airflow UI at localhost:8080

* Example DAGs after logging into Airflow

See screenshots and steps by step details below:


#### 1. Create a folder on VSCode

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/f3d6dc11-8e65-4680-b13a-fdd2d114781b" />

---

#### 2.  Ensure that Docker is running on your system, then navigate to the Airflow homepage and if on Linux system, curl the docker compose yaml files

 ```ruby
   curl -LfO 'https://airflow.apache.org/docs/apache-airflow/3.1.0/docker-compose.yaml'
 ```
If on Windows (Powershell), use the following command:

 ```ruby
  Invoke-WebRequest -Uri "https://airflow.apache.org/docs/apache-airflow/3.1.0/docker-compose.yaml" -OutFile "docker-compose.yaml"

```

<img width="1332" height="502" alt="Image" src="https://github.com/user-attachments/assets/60bf3e26-3442-4812-aceb-4c8d78022f0a" />

---



