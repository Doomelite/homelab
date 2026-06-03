# Nextcloud

## Purpose

Self-hosted cloud platform for file storage, synchronization and sharing.

## Access

URL:

* http://nextcloud.lab/
* http://SERVER_IP:8082

## Database

Backend database:

* PostgreSQL

Database host:

* postgres

Database name:

* nextcloud

## Storage

Persistent application data is stored in Docker volume:

* nextcloud_data

## Features

* File storage and synchronization
* Web access to files
* Mobile and desktop clients
* User management
* File sharing
* Calendar and contacts support

## Configuration

Trusted domains:

* nextcloud.lab
* SERVER_IP

## Dependencies

Required services:

* PostgreSQL
* Nginx Proxy Manager
* AdGuard Home
