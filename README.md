# docker-traefik

This is the updated docker-compose repo of all the media and home server apps that I currently use.

## Traefik 2 (CURRENT - GENERIC LINUX)

- docker-compose-t2.yml

### FRONTENDS

- Traefik - Reverse Proxy
- Portainer - Container Management
- Organizr - Unified Frontend

### SMART HOME

- Home Assistant Core - Home Automation

### DATABASE

- phpMyAdmin - Database management
- InfluxDB - Database for sensor data
- Grafana - Graphical data visualization for InfluxDB data

### NETWORK

- Cloudflared proxy-dns DoH
- Unifi Controller - containerized version of Ubiquiti Network's Unifi Controller
- Unifi Poller - Unifi Controller data collector

### DOWNLOADERS

- Deluge with VPN

### INDEXERS

- Jackett - Torrent proxy

### PVRS

- Lidarr - Music Management
- Radarr - Movie management
- Sonarr - TV Shows management

### MEDIA SERVER

- Emby - Media Server

### SYSTEM

- Dozzle - Docker logs viewer

### MAINTENANCE

- Watchtower - Automatic Docker Container Updates
- Docker-GC - Automatic Docker Garbage Collection
- Traefik Certificate Dumper - Extract Traefik SSL Certs
- Cloudflare DDNS - Dynamic IP Updater
- Slack-docker - A Slack integration to notify Docker events.
