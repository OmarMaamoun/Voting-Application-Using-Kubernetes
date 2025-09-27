# 🗳️ Voting-Application-Using-Kubernetes  

A demo voting application deployed on **Kubernetes** using declarative manifests and Ingress.  
This project showcases how to orchestrate a **multi-service microservices app** with **Kubernetes, Minikube, and kubectl**.  

---

## 📖 Overview  

The application is a Kubernetes-based deployment of the classic Docker Voting App.  
It demonstrates:  
- Multi-container orchestration  
- Networking with Services & Ingress  
- Stateful storage with PostgreSQL  
- Declarative Kubernetes manifests for reproducible deployments  

---

## 🏗️ Architecture  

The app consists of **5 core components**:  

1. **Vote** → 🐍 Python/Flask web app for casting votes  
2. **Redis** → ⚡ In-memory database for collecting votes  
3. **Worker** → ⚙️ .NET worker service that transfers votes from Redis → PostgreSQL  
4. **DB (PostgreSQL)** → 🗄️ Relational database for persistent storage  
5. **Result** → 🌐 Node.js web app for displaying results  

---
