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

Internet / Tailscale
        │
        ▼
AdGuard Home (DNS)
        │
        ▼
Nginx Proxy Manager
        │
 ┌──────┼────────┬────────┬─────────┐
 ▼      ▼        ▼        ▼         ▼
Homepage Portainer Kuma FileBrowser Nextcloud
                               │
                               ▼
                          PostgreSQL
