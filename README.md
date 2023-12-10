# MultiCloud Architecture Migration Project: COVID-19 Testing Status System

## Overview
This project showcases the migration of an "on-premises" application - a COVID-19 Testing Status System - to a MultiCloud Architecture. The project demonstrates the use of various technologies and cloud services to create a robust, scalable, and efficient cloud-based system.

## Technologies Used
- **Terraform**: Infrastructure as Code for provisioning on AWS and GCP.
- **Kubernetes (GKE)**: Application deployment and orchestration.
- **HTML, CSS, JavaScript**: Front-end development.
- **AWS S3**: Storage of PDF files.
- **Google Cloud Platform (GCP)**: Cloud SQL for database and Container Registry for Docker images.
- **Shell Scripting**: Automation of environment setup and configurations.
- **SQL**: Database management and migration.
- **Python**: Backend development for the web application.
- **Flask**: Python web framework for building the web application.

## Implementation

### AWS Setup
- Configured IAM user for programmatic access to AWS services, especially S3.

### GCP Configuration
- Set up Cloud SQL in GCP for the application database.
- Utilized Google Container Registry for Docker image management.

### Terraform Configuration
- Infrastructure provisioning with Terraform for both AWS and GCP services.

### Kubernetes Deployment in GKE
- Deployed the application on GKE for enhanced scalability and management.

### Data Migration
- SQL scripts and CLI operations for database migration to Cloud SQL.
- Synchronized PDF files containing COVID-19 test results to AWS S3.

### Testing and Validation
- Comprehensive testing to ensure full functionality and data integrity post-migration.

## Mockup Images
Here are some of the mockup images showcasing the key interfaces and architecture of the project:

![Hotel Home Page](/img/homepage.jpeg)
![Covid Results Records Page](/img/recordspage.jpeg)
![AWS IAM Users](/img/AWS_IAMusers.jpeg)
![AWS S3 Bucket](/img/AWS_s3bucket.jpeg)
![GKE Cluster](/img/GKE_cluster.jpeg)
![GKE Deployment](/img/GKE_deployment.jpeg)
![Google Cloud SQL database](SQLdatabse.jpeg)
![Multi Cloud Resource Destruction](/img/destroy.jpeg)

## Challenges and Learnings
The project provided practical experience in MultiCloud architecture, focusing on integrating AWS and GCP services. It also enhanced my skills in Terraform, Kubernetes, and cloud-native applications.

---

**Disclaimer**: This project is for educational purposes and might require additional security and performance enhancements for production deployment.

