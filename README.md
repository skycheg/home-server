cat > README.md << 'EOF'
# Home Media Server

## Services
- **Navidrome** :4533 — music streaming (Subsonic API)
- **Transmission** :9091 — torrent client
- **MiniDLNA** :8200 — DLNA for local network

## Stack
- Ubuntu 24.04
- Docker + Docker Compose
- CrowdSec — brute force protection
- DDNS: skycheg.mooo.com

## Usage
```bash
docker compose up -d
```
