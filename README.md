# CS 816 - Software Production Engineering Mini Project

## Scientific Calculator with DevOps

This project implements a scientific calculator with the following functionalities:

- Square root function - √x
- Factorial function - x!
- Natural logarithm (base е) - ln(x)
- Power function - x^b

## DevOps Tool Chain

### 1. Source Control Management

The source code for the project is hosted on GitHub. [GitHub Repository Link](https://github.com/bhumika-16/SPE-Calculator-Java.git)

### 2. Testing

JUnit is used for testing the calculator functions. Test cases can be found in the `tests` directory.

### 3. Build

Maven is used to build the project. The `pom.xml` file contains the build configuration.

### 4. Continuous Integration

Jenkins is employed for continuous integration. The Jenkinsfile in the repository defines the pipeline.

### 5. Containerize

Docker is used to containerize the application. The Dockerfile is included in the repository.

### 6. Push Docker Image

Docker images are pushed to Docker Hub. [Docker Hub Repository Link](https://hub.docker.com/repository/docker/bhumika16/calculator-java/general)

### 7. Deployment

Configuration management and deployment are handled by Ansible. Ansible playbooks definitions are available in the `ansible` directory.

### 8. Deployment Targets

Deployment is done locally now, which may later be deployed on a Kubernetes cluster, OpenStack cloud, or third-party clouds like AWS, GCP, etc.

## Submission

### Report

- [Project Report PDF](https://github.com/bhumika-16/SPE-Calculator-Java.git)
- Each step is explained in the report, including tools used, setup, configurations, commands, and screenshots.

### GitHub Repository

[GitHub Repository Link](https://github.com/bhumika-16/SPE-Calculator-Java.git)

### Docker Hub Repository

[Docker Hub Repository Link](https://hub.docker.com/repositories/bhumika16)

### Zipped Folder

The zipped folder is named `MT2023005.zip` and contains screenshot images and the PDF report.

## Running the Application

Instructions for running the scientific calculator application can be found in the Report attached.

---
