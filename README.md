# SIT737-2025-Prac5D: Dockerization & Cloud Publishing

## ✅ What This Project Does

Dockerized Node.js microservices and published them to Google Cloud Artifact Registry.

## 🧱 Microservices

- Calculator Service
- Gateway Service
- Log Service

## 🚀 Deployment Steps

1. **Build Docker images locally**
2. **Authenticate to Google Cloud**
3. **Push images to Artifact Registry**
4. **Run microservices from cloud images**
5. **Test with Docker Compose**

## 📂 Registry Path

australia-southeast2-docker.pkg.dev/sit707-25t1-tepaiyan-8729201/my-docker-repo/calculator-service

australia-southeast2-docker.pkg.dev/sit707-25t1-tepaiyan-8729201/my-docker-repo/gateway-service

push australia-southeast2-docker.pkg.dev/sit707-25t1-tepaiyan-8729201/my-docker-repo/log-service

## 🧪 Testing Locally

```bash
docker-compose up

🔐 Auth Command
gcloud auth configure-docker australia-southeast1-docker.pkg.dev

```
