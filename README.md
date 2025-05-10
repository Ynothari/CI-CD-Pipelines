# 🚀 Jenkins CI/CD Pipeline with Docker and Kubernetes

This project demonstrates a complete CI/CD pipeline using **Jenkins**, **Docker**, and **Kubernetes**, by deploying a simple Flask "Hello World" application. It's a hands-on guide for DevOps beginners and enthusiasts looking to learn the essentials of pipeline automation, containerization, and orchestration.

---

## 🛠️ Project Overview

- **Project Name**: CI/CD Pipeline with Jenkins, Docker, and Kubernetes  

### 🌐 Application

A basic Flask app (`Hello World`) that will be containerized, built via Jenkins, and deployed on Kubernetes.

---

## 🧱 Tech Stack

| Tool            | Purpose                    |
|-----------------|----------------------------|
| **Jenkins**     | CI/CD Automation           |
| **Docker**      | Containerization           |
| **Kubernetes**  | Container Orchestration    |
| **Flask (Python)** | Web Application          |
| **Minikube**    | Local Kubernetes Cluster   |
| **GitHub**      | Version Control and Integration |

---

## 📁 Project Structure

```bash
.
├── Dockerfile              # Docker configuration for Flask app
├── app.py                  # Flask "Hello World" application
├── requirements.txt        # Python dependencies
├── jenkins_pipeline.groovy # Jenkins declarative pipeline
├── jenkins_setup.sh        # Script to install Jenkins locally
├── jenkins_plugins.txt     # List of required Jenkins plugins
├── k8s/
│   └── deployment.yaml     # Kubernetes deployment file
└── README.md               # Project overview
