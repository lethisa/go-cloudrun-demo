# GCP Cloud Run CI/CD with Terraform

This project demonstrates how to build a simple **CI/CD pipeline on Google Cloud Platform (GCP)** using:

- **Terraform** for Infrastructure as Code
- **Cloud Build** to build container images
- **Artifact Registry** to store container images
- **Cloud Run** to run the containerized application
- **GitHub** as the source code repository

The pipeline automatically performs the following steps:

1. Source code is pushed to GitHub
2. Cloud Build is triggered
3. The application is built into a Docker image
4. The image is pushed to Artifact Registry
5. Cloud Run deploys the application using the new image

by : Lethisa
