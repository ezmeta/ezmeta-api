# EZMeta API Server

AI-powered Meta Ads monitoring system.

## Deploy to Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app)

## Local Development

```bash
pip install -r requirements.txt
uvicorn ezmeta_server_v3:app --reload --port 8888
```

## API Endpoints

- `GET /` - Server status
- `GET /data` - Get campaign data
- `GET /clients` - List all clients
- `POST /clients` - Add new client
- `POST /register` - Client self-register
- `POST /auth/login` - Login
- `POST /scan/all` - Scan all clients
