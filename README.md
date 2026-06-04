# Vanderbilt University (vanderbilt)

Vanderbilt University is a private research university in Nashville, Tennessee, ranked #248 in the QS World University Rankings 2025. This repository catalogs Vanderbilt's public developer and API footprint as an [APIs.json](https://apisjson.org) profile. That footprint is limited and largely gated: Vanderbilt IT (VUIT) offers API integration and management services to faculty and staff behind an Azure API Management portal that does not resolve for the general public, while the Heard Libraries and Data Science Institute maintain open GitHub presences. No official, publicly documented, self-service Vanderbilt API was confirmed during review.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/vanderbilt/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=vanderbilt-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Research, Nashville, Tennessee, United States

## APIs

- **Vanderbilt API Management Developer Portal** — Azure API Management portal for discovering APIs, acquiring keys, and trying APIs interactively. Appears internal/network-gated (did not resolve publicly during review). Docs: https://apim-portal.app.vanderbilt.edu/
- **Vanderbilt IT API Services** — VUIT Cloud Services integration and custom REST API development for faculty/staff (consulting service, not a public API product). Docs: https://it.vanderbilt.edu/services/catalog/infrastructure/middleware/application_program_interface_services.php

## Plans, Rate Limits, and FinOps

- Plans & Pricing: [plans/vanderbilt-plans-pricing.yml](plans/vanderbilt-plans-pricing.yml)
- Rate Limits: [rate-limits/vanderbilt-rate-limits.yml](rate-limits/vanderbilt-rate-limits.yml)
- FinOps: [finops/vanderbilt-finops.yml](finops/vanderbilt-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.vanderbilt.edu/
- GitHub (official): https://github.com/vanderbiltu
- Source Code (Heard Libraries): https://github.com/heardlibrary
- LinkedIn: https://www.linkedin.com/school/vanderbilt-university/
- Developer Portal: https://apim-portal.app.vanderbilt.edu/
- Review: [review.yml](review.yml)

## Notes

Verification caveats (probed 2026-06-03):

- The official Vanderbilt GitHub org (`vanderbiltu`) exists but has zero public repositories.
- The Azure API Management developer portal endpoint did not resolve externally — it appears to be internal/network-gated, not openly self-service.
- VUIT "API Services" is a faculty/staff integration consulting offering, not a documented public API.
- The library runs Ex Libris Alma/Primo (which supports OAI-PMH and discovery APIs), and the Heard Libraries and Data Science Institute GitHub orgs host open code, but no Vanderbilt-specific public API documentation was confirmed.
- No endpoints were fabricated; entries reflect only what was confirmed by reference or live probe.

## Maintainers

- Kin Lane — kin@apievangelist.com
