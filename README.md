# Homelab

Personal homelab project used for learning Linux administration, Docker and DevOps fundamentals.

## Technologies

- Ubuntu Server
- Docker
- Docker Compose
- Portainer
- Homepage
- Uptime Kuma
- Nginx Proxy Manager
- Tailscale
- AdGuard Home
- PostgreSQL
- Adminer
- Nextcloud

## Goals

- Learn Linux
- Learn Docker
- Learn networking
- Build a portfolio for Junior Linux / DevOps roles

## Architecture

## Homelab Architecture

```text
                         ┌─────────────┐
                         │  Tailscale  │
                         └──────┬──────┘
                                │
                                ▼
                         ┌─────────────┐
                         │ AdGuard DNS │
                         └──────┬──────┘
                                │
                                ▼
                   ┌────────────────────────┐
                   │ Nginx Proxy Manager    │
                   └──────────┬─────────────┘
                              │
      ┌────────────┬──────────┼──────────┬────────────┬────────────┐
      ▼            ▼          ▼          ▼            ▼            ▼
 Homepage      Portainer  FileBrowser  UptimeKuma  Adminer    Nextcloud
                                                               │
                                                               ▼
                                                          PostgreSQL
```
