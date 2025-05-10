# Jenkins CI/CD Pipeline with Docker and Kubernetes

This project demonstrates a simple CI/CD pipeline setup using Jenkins, Docker, and Kubernetes. It deploys a basic Flask "Hello World" application, providing a practical introduction to DevOps principles.

## 🔧 Tech Stack

- **CI/CD Tool**: Jenkins
- **Containerization**: Docker
- **Orchestration**: Kubernetes (Minikube)
- **App**: Flask (Python)

## 📁 Folder Structure

```bash
.
├── Dockerfile              # Docker configuration for Flask app
├── app.py                  # Flask application (Hello World)
├── requirements.txt        # Python dependencies
├── jenkins_pipeline.groovy # Jenkins Declarative Pipeline
├── jenkins_setup.sh        # Script to install Jenkins locally
├── jenkins_plugins.txt     # Jenkins plugins list
└── README.md               # Project overview
