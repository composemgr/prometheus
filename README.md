## 👋 Welcome to prometheus 🚀

Prometheus - Monitoring system and time series database

## 📋 Description

Prometheus is an open-source systems monitoring and alerting toolkit. Collects and stores metrics as time series data.

## 🚀 Services

- **app**: Prometheus (`prom/prometheus:latest`)

## 📦 Installation

```shell
composemgr install prometheus
```

## 🔧 Configuration

Edit `rootfs/config/prometheus/prometheus.yml` to configure scrape targets.

## 🌐 Access

- **Prometheus**: http://localhost:9090

## 📂 Volumes

- `./rootfs/config/prometheus` - Configuration files
- `./rootfs/data/prometheus` - Time series data

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
