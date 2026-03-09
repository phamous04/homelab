# Immich

This directory contains the documentation and configuration structure for the Immich deployment in the homelab.

## Deployment Summary

- App: Immich
- Compute host: MacBook (M2)
- NAS: WD MyCloud EX2 Ultra
- Storage model:
  - Originals stored on NAS
  - Database, thumbnails, and generated runtime data stored locally where appropriate

## Important Notes

- Do not commit live `.env` files with secrets
- Do not commit runtime folders or media libraries
- Keep production storage paths out of version control unless redacted or templated

## Directory Layout

- `compose/` → Docker Compose files
- `env/` → sample environment files
- `scripts/` → app-specific helper scripts
- `docs/` → deployment notes, migrations, and troubleshooting

cat > apps/immich/README.md <<'EOF'
# Immich

This directory contains the documentation and configuration structure for the Immich deployment in the homelab.

## Deployment Summary

- App: Immich
- Compute host: MacBook (M2)
- NAS: WD MyCloud EX2 Ultra
- Storage model:
  - Originals stored on NAS
  - Database, thumbnails, and generated runtime data stored locally where appropriate

## Important Notes

- Do not commit live `.env` files with secrets
- Do not commit runtime folders or media libraries
- Keep production storage paths out of version control unless redacted or templated

## Directory Layout

- `compose/` → Docker Compose files
- `env/` → sample environment files
- `scripts/` → app-specific helper scripts
- `docs/` → deployment notes, migrations, and troubleshooting

