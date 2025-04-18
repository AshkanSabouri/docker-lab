# 🚀 Docker Lab

Welcome to **Docker Lab** – your all-in-one playground for Dockerized developer tools and services.

This repository contains pre-configured Docker Compose files and Dockerfiles for commonly used services like:

- 🧰 GitLab
- 🐳 Portainer (Soon)
- 📈 Grafana + Prometheus (Soon)
- 📁 MinIO (Soon)
- 🛠️ Jenkins (Soon)
- 🧪 and more...

## 📦 What's Included

| Service     | Description                   | Directory        |
|-------------|-------------------------------|------------------|
| GitLab      | Self-hosted Git platform       | `/gitlab`        |


## 📂 Structure

Each service lives in its own directory, with:

- `docker-compose.yml`
- `.env.example`
- Service-specific setup and notes

## 🚀 Getting Started

```bash
cd <service-directory>
cp .env.example .env
docker-compose up -d
