# 1. a-reddit-clone-gitops

This project demonstrates the deployment of a Reddit clone application using a GitOps approach.  
It leverages Kubernetes for container orchestration, Jenkins for continuous integration and deployment (CI/CD), and Terraform for infrastructure provisioning.

# 2. 🛠️ Technologies Used

1. **Kubernetes**: Container orchestration  
2. **Jenkins**: CI/CD automation  
3. **Terraform**: Infrastructure as Code  
4. **Docker**: Containerization  
5. **GitOps**: Declarative infrastructure management  

# 3. 🚀 Project Overview

This project automates the deployment of a Reddit clone application using a GitOps workflow.  
The process involves:

1. **Infrastructure Provisioning**: Using Terraform to set up the necessary infrastructure.  
2. **CI/CD Pipeline**: Configuring Jenkins to automate the build, test, and deployment processes.  
3. **Application Deployment**: Deploying the application to a Kubernetes cluster.  
4. **Monitoring**: Setting up monitoring tools to observe the application's performance.  

# 4. 📁 Project Structure

The repository contains the following key files:

1. `Jenkinsfile`: Defines the Jenkins pipeline for CI/CD.  
2. `deployment.yaml`: Kubernetes deployment configuration.  
3. `service.yaml`: Kubernetes service configuration.  
4. `README.md`: Project documentation.  

# 5. 🧪 Getting Started

## 5.1 Prerequisites

1. Docker  
2. Jenkins  
3. Terraform  
4. Kubernetes Cluster  

## 5.2 Setup Instructions

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Hamzaakk/a-reddit-clone-gitops.git
   cd a-reddit-clone-gitops
