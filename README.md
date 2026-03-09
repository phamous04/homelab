cat > README.md <<'EOF'
# Homelab

A self-hosted homelab repository for documenting and managing my home infrastructure and services.

## Overview

This repository tracks the configuration, documentation, and operational notes for my homelab. It started with a Western Digital MyCloud EX2 Ultra NAS and an Immich deployment running on a MacBook, and is structured to scale as I add more self-hosted services over time.

## Hardware

- Server compute: Apple MacBook (M2)
- Network storage: Western Digital MyCloud EX2 Ultra NAS

## Current Services

- Immich
  - Self-hosted photo and video management
  - Originals stored on NAS
  - Performance-sensitive data stored locally on the MacBook
- More services will be added over time

## Repository Structure

- `apps/` → per-application configs and docs
- `docs/` → architecture, networking, operations, and runbooks
- `scripts/` → helper scripts for backup, restore, and maintenance
- `infrastructure/` → shared infrastructure docs and config references

## Prerequisites

- macOS terminal access
- Git
- GitHub CLI (`gh`)
- Docker Desktop
- Access to the NAS share
- Cloudflare account and domain if remote access is enabled

## Replicating the Setup

1. Clone this repository
2. Review the docs in `docs/`
3. Copy example environment files and customize them
4. Start the desired app stack from its app directory
5. Validate storage mounts, networking, and backups

## Notes

- Secrets and live runtime data are intentionally excluded from version control
- This repo is meant to document the setup, not store production media or databases

## Apps

### Immich
See:
- `apps/immich/README.md`
- `apps/immich/compose/docker-compose.yml`
- `apps/immich/docs/`

