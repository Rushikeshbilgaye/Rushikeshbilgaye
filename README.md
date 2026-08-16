# 👋 Hi, I'm Rushikesh Bilgaye

### 🚀 DevOps Engineer | AWS | Kubernetes | Terraform | Jenkins | CI/CD

I am a DevOps and Cloud enthusiast focused on building, automating, and deploying scalable cloud-native applications.

I work with **AWS, Linux, Docker, Kubernetes, Terraform, Jenkins, GitHub Actions, and CI/CD** to automate infrastructure provisioning, application deployments, and cloud operations.

---

## 🧑‍💻 About Me

* ☁️ Building and deploying applications on **AWS Cloud**
* ☸️ Working with **Kubernetes & Amazon EKS**
* 🔄 Building automated **CI/CD pipelines**
* 🏗️ Practicing **Infrastructure as Code using Terraform**
* 🐳 Containerizing applications using **Docker**
* ⚙️ Automating deployments with **Jenkins & GitHub Actions**
* ☁️ Building **serverless applications using AWS Lambda**
* 🐧 Working with **Linux & Shell Scripting**
* 📊 Exploring **Monitoring & Observability**
* 🎯 Preparing for **DevOps / Cloud Engineer opportunities**

---

# 🛠️ Tech Stack

### ☁️ Cloud — AWS

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge\&logo=amazonaws\&logoColor=white)

**EC2 • VPC • IAM • S3 • EBS • ELB • Auto Scaling • Route 53 • CloudWatch • RDS • Lambda • API Gateway • DynamoDB • EKS**

### 🐧 Linux

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)

**Ubuntu • Linux Administration • Shell Scripting • System Monitoring • Networking**

### 🔀 Git & GitHub

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)

**Git • GitHub • Branching • Merging • Pull Requests • Git Workflows**

### 🐳 Docker

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)

**Docker • Dockerfile • Docker Compose • Container Networking • Docker Hub**

### ☸️ Kubernetes

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge\&logo=kubernetes\&logoColor=white)

**Kubernetes • Amazon EKS • Pods • Deployments • Services • ConfigMaps • Secrets • Ingress • Namespaces**

### 🏗️ Infrastructure as Code

![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge\&logo=terraform\&logoColor=white)

**Terraform • Modules • Variables • Outputs • State Management • Remote Backend • AWS Infrastructure**

### 🔄 CI/CD

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge\&logo=jenkins\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge\&logo=githubactions\&logoColor=white)

**Jenkins • Jenkinsfile • GitHub Actions • CI/CD Pipelines • Docker CI/CD • Automated Deployments**

### 📊 Monitoring

**Prometheus • Grafana • AWS CloudWatch**

---

# 🚀 Featured DevOps Projects

## 1️⃣ Hybrid Cloud-Native Architecture on Amazon EKS using Jenkins

### 📌 Project Overview

Designed and deployed a **hybrid application architecture combining containerized and serverless components** on AWS, with **Amazon EKS** as the container orchestration platform.

The deployment process is automated using **Jenkins CI/CD**, enabling automated application builds, containerization, and deployment.

### 🏗️ Architecture

```text
                    Developer
                        |
                        ↓
                     GitHub
                        |
                        ↓
                    Jenkins
                        |
              ┌─────────┴─────────┐
              ↓                   ↓
        Docker Build        Serverless Components
              |                   |
              ↓                   ↓
         Container Image      AWS Lambda
              |                   |
              ↓                   ↓
        Amazon ECR           API Gateway
              |                   |
              ↓                   ↓
          Amazon EKS          DynamoDB
              |
              ↓
       Containerized App
```

### 🛠️ Technologies

**AWS • Amazon EKS • Kubernetes • Docker • Jenkins • GitHub • Amazon ECR • Lambda • API Gateway • DynamoDB • IAM**

### 🔧 Key Implementation Areas

* Containerized application using **Docker**
* Deployed containerized workloads on **Amazon EKS**
* Configured **Kubernetes Deployments and Services**
* Built CI/CD pipeline using **Jenkins**
* Automated Docker image build and deployment
* Used **Amazon ECR** for container image storage
* Integrated serverless components using **AWS Lambda**
* Used **API Gateway** for serverless API integration
* Used **DynamoDB** for serverless data storage
* Configured AWS IAM permissions
* Implemented a hybrid **containerized + serverless architecture**

🔗 **Repository:** `YOUR_REPOSITORY_LINK`

---

## 2️⃣ Serverless Application using AWS Lambda, API Gateway & DynamoDB

### 📌 Project Overview

Built and deployed a **serverless application on AWS** using managed cloud services, eliminating the need to manage traditional servers.

The application uses **API Gateway** as the API layer, **AWS Lambda** for compute, and **DynamoDB** as the database.

### 🏗️ Architecture

```text
                    User
                      |
                      ↓
                API Gateway
                      |
                      ↓
                 AWS Lambda
                      |
                      ↓
                  DynamoDB
                      |
                      ↓
                  Response
```

### 🛠️ Technologies

**AWS Lambda • API Gateway • DynamoDB • IAM • CloudWatch**

### 🔧 Key Implementation Areas

* Created and configured **AWS Lambda functions**
* Built REST APIs using **Amazon API Gateway**
* Integrated API Gateway with Lambda
* Designed a serverless data layer using **DynamoDB**
* Configured **IAM roles and permissions**
* Used **CloudWatch** for logging and monitoring
* Tested API endpoints and Lambda functionality
* Designed a scalable and cost-efficient serverless architecture

🔗 **Repository:** `YOUR_REPOSITORY_LINK`

---

## 3️⃣ Hybrid Cloud-Native Architecture on Amazon EKS using GitHub Actions

### 📌 Project Overview

Implemented a **hybrid application architecture combining containerized workloads with AWS serverless services** and automated the deployment process using **GitHub Actions**.

The project demonstrates a modern cloud-native CI/CD workflow from source code commit to deployment on Amazon EKS.

### 🏗️ Architecture

```text
                    Developer
                        |
                        ↓
                     GitHub
                        |
                        ↓
                GitHub Actions
                        |
              ┌─────────┴─────────┐
              ↓                   ↓
        Docker Build        Deployment Automation
              |                   |
              ↓                   ↓
         Amazon ECR          Amazon EKS
                                  |
                         ┌────────┴────────┐
                         ↓                 ↓
                  Kubernetes Pods      Services
                         |
                         ↓
                 Containerized App


              Serverless Layer
                     |
                     ↓
                API Gateway
                     |
                     ↓
                 AWS Lambda
                     |
                     ↓
                 DynamoDB
```

### 🛠️ Technologies

**AWS • Amazon EKS • Kubernetes • Docker • GitHub Actions • Amazon ECR • Lambda • API Gateway • DynamoDB • IAM**

### 🔧 Key Implementation Areas

* Managed source code using **GitHub**
* Created automated CI/CD workflow using **GitHub Actions**
* Built Docker images automatically
* Pushed container images to **Amazon ECR**
* Automated deployment to **Amazon EKS**
* Configured Kubernetes Deployments and Services
* Integrated serverless components using **AWS Lambda**
* Connected APIs through **API Gateway**
* Used **DynamoDB** as the serverless database
* Configured AWS credentials and IAM permissions for CI/CD
* Implemented automated build and deployment workflow

🔗 **Repository:** `YOUR_REPOSITORY_LINK`

---

# 🔄 DevOps CI/CD Workflow

```text
Developer
    |
    ↓
 GitHub
    |
    ├───────────────┐
    ↓               ↓
 Jenkins       GitHub Actions
    |               |
    └───────┬───────┘
            ↓
       Docker Build
            |
            ↓
        Amazon ECR
            |
            ↓
        Amazon EKS
            |
            ↓
     Kubernetes Workloads
            |
            ↓
       Application
```

---

# ☁️ Hybrid Architecture

```text
                    AWS Cloud
                       |
          ┌────────────┴────────────┐
          |                         |
          ↓                         ↓
    Containerized               Serverless
      Workloads                  Workloads
          |                         |
      Amazon EKS                API Gateway
          |                         |
      Kubernetes                 Lambda
          |                         |
       Docker                  DynamoDB
          |
      Amazon ECR
```

---

# 📚 Currently Learning

* ☸️ Advanced Kubernetes & Amazon EKS
* 🏗️ Advanced Terraform
* 🔄 CI/CD Automation
* ☁️ AWS Cloud-Native Architecture
* 📊 Prometheus & Grafana
* 🔐 DevSecOps
* ⚙️ Cloud Automation
* 🚀 Scalable & Highly Available Infrastructure

---

# 🎯 DevOps Learning Journey

```text
Linux
  ↓
Git & GitHub
  ↓
AWS
  ↓
Docker
  ↓
Jenkins / CI-CD
  ↓
Terraform
  ↓
Kubernetes / EKS
  ↓
Serverless
  ↓
Monitoring & Observability
  ↓
Cloud-Native DevOps
```

---

# 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME\&show_icons=true\&theme=tokyonight)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME\&layout=compact\&theme=tokyonight)

---

# 🤝 Connect With Me

📧 **Email:** YOUR_EMAIL

💼 **LinkedIn:** YOUR_LINKEDIN_URL

🐙 **GitHub:** https://github.com/YOUR_GITHUB_USERNAME

---

## ⚡ DevOps Mindset

> **Automate everything that can be automated.
> Build reliable infrastructure.
> Monitor what matters.
> Learn from every failure.**

---

⭐ **Feel free to explore my repositories and connect with me!**

### 🚀 Building. Automating. Deploying.
