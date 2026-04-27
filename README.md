# 🚀 DevOps Observability Stack (Grafana + Prometheus + Node Exporter)

A complete real-time system monitoring and observability project built using Docker. It collects system metrics (CPU, memory, disk, network) and visualizes them using Grafana dashboards.

---

# 📌 Overview

This project demonstrates a full DevOps observability pipeline:

- System metrics are collected using Node Exporter
- Prometheus scrapes and stores the metrics
- Grafana visualizes the data in real-time dashboards

This replicates how real production systems (cloud servers, Kubernetes clusters, AWS environments) are monitored in industry.

---

# 🧱 Architecture

System (Host Machine)
        ↓
Node Exporter (collects metrics)
        ↓
Prometheus (stores & scrapes metrics)
        ↓
Grafana (visualizes dashboards)

---

# 🛠️ Tech Stack

- Grafana – Visualization & dashboards  
- Prometheus – Metrics collection & storage  
- Node Exporter – System-level metrics (CPU, RAM, Disk)  
- Docker – Containerization platform  

---

# 📊 Features

✔ Real-time system monitoring  
✔ CPU usage tracking  
✔ Memory usage tracking  
✔ Disk usage monitoring  
✔ Network traffic monitoring  
✔ Live Grafana dashboards  
✔ Docker-based deployment  

---

# ⚙️ Project Setup

## 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/observability-project.git
cd observability-project
