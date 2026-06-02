# Nginx Proxy Manager

## Purpose

Reverse proxy for homelab services.

## Acces

- http://<server-ip>:81

## Docker Image

- jc21/nginx-proxy-manager:2.15.0

## Persisten Data

- .data:/data

- ./letsencrypt:/etc/letsencrypt

## Notes

- Used to expose services through user-friendly hostnames.

## Examples:

- homepage.lab -> Homepage

- kuma.lab -> Uptime Kuma

- portainer.lab -> Portainer

## Future improvement:

- Deploy local DNS server (Probably AdGuard Home)

- Configure HTTPS certificates
