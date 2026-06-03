# PostgreSQL + Adminer

## Purpose

This database stack is used as backedn service for self-hosted applications such as Nextcloud

## Components

- PostgreSQL 17 - relational database server

- Adminer - lightweight web-based database administration tool

## Access

## PostgreSQL

Internal Docker hostname:

- postgres

Container name:

- postgresql

Default port:

- 5432

## Adminer

- http://adminer.lab

- http://server-ip:8081

## Configuration

- POSTGRES_DB=nextcloud

- POSTGRES_USER=nextcloud

- POSTGRES_PASSWORD=your_secure_password

## Storage

Persistend database data is stored in Docker volume:

- postgres_data


