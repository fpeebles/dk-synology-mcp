# Synology MCP Server Roadmap

Roadmap for the Synology NAS management MCP server.

## Current State

- The product already has a broad tool surface and strong feature promise.
- The next work is setup reliability, auth hardening, and operator-facing maturity.

## Phase 1 — Setup And Auth Reliability
- [ ] Tighten configuration, connectivity validation, and multi-NAS onboarding.
- [ ] Improve auth flows for HTTPS, OTP, and delegated account usage.
- [ ] Add clearer failure reporting for DSM compatibility and permission problems.

## Phase 2 — Tool-Surface Hardening
- [ ] Prioritize the highest-value tool families for deeper validation and examples.
- [ ] Improve consistency across tool outputs and error models.
- [ ] Add stronger safeguards for destructive or high-impact operations.

## Phase 3 — Packaging And Release Quality
- [ ] Improve install and deployment guidance for local and hosted MCP clients.
- [ ] Add regression checks around supported DSM versions and major service families.
- [ ] Tighten release/versioning discipline for a broad tool surface.

## Phase 4 — Docs And Real-World Workflows
- [ ] Add richer examples for file, backup, Docker, and virtualization workflows.
- [ ] Improve operator guidance for multi-NAS environments.
- [ ] Decide what remains a power-user MCP surface versus what deserves higher-level workflow abstractions.
