## 👋 Welcome to prometheus 🚀

Open-source monitoring and alerting toolkit

## 📋 Description

Open-source monitoring and alerting toolkit

## 🚀 Services

- **app**: prom/prometheus:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/prometheus/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/prometheus" ~/.local/srv/docker/prometheus
cd ~/.local/srv/docker/prometheus
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install prometheus
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:9090

## 📂 Volumes

- `./volumes/config/prometheus` - Data storage
- `./volumes/data/prometheus` - Data storage

## 🔍 Logging

```shell
docker compose logs -f app
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
