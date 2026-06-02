# AdGuard Home

## Purpose

DNS server for homelab services and ad blocking.

## Access

http://server-ip:82

## Image

adguard/adguardhome:latest

## Persisten Data

- adguard_work:/opt/adguardhome/work

- adguard_conf:/opt/adguardhome/conf

## DNS Rewrites

- homepage.lab -> 100.121.236.113

- uptimekuma.lab -> 100.121.236.113

- portainer.lab -> 100.121.236.113

- filebrowser.lab -> 100.121.236.113

- nginxproxymanager.lab -> 100.121.236.113

## Notes

Used for local DNS records and network-wide ad blocking.

Currently running without DNS port 53 due to systemd-resolved conflict.

## Future Improvements

- Replace systemd-resolved and bind AdGuard to port 53

- Integrate with Tailscale DNS

- Enable DNS filtering for all homelab devices

- Configure HTTPS for admin panel
