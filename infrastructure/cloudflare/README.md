# Cloudflare Setup

This homelab exposes services using Cloudflare Tunnel.

## Current Tunnel

Service: Immich  
Domain: photos.yourdomain.com  
Local Port: 2283  

## Setup Steps

1. Install cloudflared
2. Authenticate with Cloudflare
3. Create tunnel
4. Add DNS route
5. Run tunnel service

## Commands

cloudflared tunnel login
cloudflared tunnel create immich-tunnel
cloudflared tunnel route dns immich-tunnel photos.yourdomain.com
cloudflared tunnel run immich-tunnel
