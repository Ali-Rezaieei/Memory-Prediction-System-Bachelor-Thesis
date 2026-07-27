# Memory Prediction System (Bachelor Thesis) 🧠

A complete ecosystem for monitoring and predicting memory usage of Virtual Machines, utilizing Libvirt, Prometheus, and Machine Learning.

## 🚀 Architecture
- **Agent**: A custom `prometheus-libvirt-exporter` written in **Go** that interacts with the Libvirt API to extract real-time VM metrics and expose them to Prometheus.
- **Server**: A **Python Flask** web server acting as the backend and dashboard for visualizing data and serving predictions.
- **Containerized**: Fully Dockerized for seamless deployment.

## 🛠️ Tech Stack
- **Backend**: Go (Agent), Python Flask (Server)
- **Virtualization & Metrics**: Libvirt, Prometheus
- **Deployment**: Docker, Debian packages\n