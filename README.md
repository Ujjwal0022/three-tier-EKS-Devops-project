
# DevOps  Project: Deploying a  3-Tier MERN Application on AWS EKS Using Kubernetes and Docker.

---

## A complete enterprise-grade cloud-native deployment  implementing containerization, orchestration, scalability, networking, security, and  on Amazon EKS.

---

This project demonstrates how a modern 3-tier MERN stack application can be deployed on AWS Elastic Kubernetes Service (EKS) using industry-standard DevOps tools and production-style architecture.

The project includes Kubernetes manifests, containerized services, ingress configuration, persistent storage, load balancing  and secure deployment practices.

---

# Project Overview

This repository showcases the deployment of a scalable 3-tier architecture application consisting of:

- Frontend Tier
- Backend/API Tier
- Database Tier

All services are deployed inside a Kubernetes cluster running on AWS EKS.

---

# Architecture Highlights

- Amazon EKS Cluster
- Kubernetes Deployments and Services
- AWS Application Load Balancer
- Ingress Controller
- Persistent Volumes and Persistent Volume Claims
- Docker Containerization
- Secure Secrets Management
- Namespace Isolation
- Scalable Microservice Deployment

---

# 📂 Project Directories Overview

## 🚀 Application Code

The `Application-Code` directory contains the source code for the Three-Tier Todo Application. It includes both the frontend and backend components of the application.

- Frontend built using React.js
- Backend API developed using Node.js and Express.js
- MongoDB integration for database operations

---

## ☸️ Kubernetes Manifests Files

The `Kubernetes-Manifests-file` directory contains all Kubernetes manifest files required to deploy the application on Amazon EKS.

These manifests include:

- Deployments
- Services
- Ingress Configuration
- Namespace Configuration
- Database Resources

The files can be customized based on cluster and deployment requirements.

---

## 🌐 AWS Load Balancer Integration

The project uses Kubernetes Ingress with the AWS Load Balancer Controller to automatically provision an internet-facing Application Load Balancer (ALB).

This enables:

- External access to the application
- Traffic routing to frontend and backend services
- Scalable and cloud-native networking

---

## 🐳 Containerized Architecture

All application components are containerized using Docker and deployed as Kubernetes workloads inside the EKS cluster.

The architecture includes:

- Frontend Pod
- Backend Pod
- MongoDB Pod

---

## ⚙️ DevOps Workflow

This project demonstrates an end-to-end DevOps deployment workflow including:

- Docker Image Creation
- Kubernetes Deployment
- AWS EKS Cluster Management
- Ingress & Load Balancer Configuration
- Application Exposure using ALB DNS


# 🛠️ Tech Stack Used

---

## 🚀 Core DevOps Stack

<p align="center">

<img src="https://skillicons.dev/icons?i=github" height="60"/>
<img src="https://skillicons.dev/icons?i=docker" height="60"/>

</p>

<p align="center">
GitHub • Docker 
</p>

---

## ☸️ Kubernetes & Cloud

<p align="center">

<img src="https://skillicons.dev/icons?i=kubernetes" height="70"/>
<img src="https://helm.sh/img/helm.svg" height="70"/>
<img src="https://skillicons.dev/icons?i=aws" height="70"/>

</p>

<p align="center">
AWS EKS • Helm • AWS
</p>

---


## 💻 Application Stack

<p align="center">

<img src="https://skillicons.dev/icons?i=react" height="65"/>
<img src="https://skillicons.dev/icons?i=nodejs" height="65"/>
<img src="https://skillicons.dev/icons?i=express" height="65"/>
<img src="https://skillicons.dev/icons?i=mongodb" height="65"/>

</p>

<p align="center">
React • Node.js • Express • MongoDB
</p>

---

# 🏗️ DevSecOps Architecture
<img width="1536" height="1024" alt="eks image" src="https://github.com/user-attachments/assets/ae4062cf-eb49-4d7f-a261-e36f18fddcc1" />


## ✨ Key Features

- 🚀 Three-Tier Application Deployment on AWS EKS
- ☸️ Kubernetes-based Container Orchestration
- 🐳 Dockerized Frontend, Backend, and MongoDB Services
- 🌐 AWS Application Load Balancer (ALB) Integration
- 🔀 Kubernetes Ingress for Traffic Routing
- 📦 Scalable Cloud-Native Architecture
- ⚡ Real-Time Todo Application Functionality
- 🛠️ End-to-End DevOps Deployment Workflow


# 📸 Project Screenshots

## 🚀 Three-Tier Todo Application UI

<img width="1917" height="1017" alt="Screenshot 2026-05-11 223429" src="https://github.com/user-attachments/assets/254ee499-27f6-40b8-91c0-7707bcbe6c47" />


---

## ☸️ Running Kubernetes Pods

<img width="1478" height="335" alt="Screenshot 2026-05-12 010145" src="https://github.com/user-attachments/assets/cc685647-9807-4d82-b58b-645acbc91b45" />

---

## ☁️ AWS Application Load Balancer

<img width="1902" height="907" alt="image" src="https://github.com/user-attachments/assets/3a12e97b-4664-457a-8ee9-b72c43e4e834" />

---

## ⚙️ Amazon EKS Cluster

<img width="1896" height="900" alt="image" src="https://github.com/user-attachments/assets/c43185ba-c22f-43a2-97bc-8bb7468b1eb9" />



## 📦 Project Flow

Developer → Docker Build → DockerHub Push  
→ Kubernetes Manifests → AWS EKS Cluster  
→ AWS ALB Ingress → Application Deployment 🚀

