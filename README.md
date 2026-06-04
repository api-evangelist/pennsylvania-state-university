# Pennsylvania State University (pennsylvania-state-university)

Pennsylvania State University (Penn State) is a public, land-grant research university headquartered at University Park, PA, and ranked #69 in the QS World University Rankings 2025. This repository catalogs Penn State's public developer/API footprint as an [APIs.json](http://apisjson.org) provider profile for the api-evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/pennsylvania-state-university/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=pennsylvania-state-university-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Facilities, United States

## APIs

- **LionSpaceFIS REST API** — Office of Physical Plant facilities/space data (buildings, rooms, campuses, events). Verified live and public. Docs: https://apps.opp.psu.edu/fis-api/
- **Researcher Metadata Database (RMD) API** — University Libraries researcher/publication metadata via an OpenAPI-described REST API; requires a license key. Docs: https://metadata.libraries.psu.edu/api_docs
- **Penn State IT Web Developer Services** — Portal cataloging internal REST services (PSU ID, Academic Course, Cornerstone, Sponsored Accounts, ASR Lookup); reference pages are behind Shibboleth SSO. Docs: https://docs.developer.psu.edu/

## Plans

- [plans/pennsylvania-state-university-plans-pricing.yml](plans/pennsylvania-state-university-plans-pricing.yml)

## Rate Limits

- [rate-limits/pennsylvania-state-university-rate-limits.yml](rate-limits/pennsylvania-state-university-rate-limits.yml)

## FinOps

- [finops/pennsylvania-state-university-finops.yml](finops/pennsylvania-state-university-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.psu.edu/
- Developer Portal: https://docs.developer.psu.edu/
- GitHub (open source): https://github.com/PennState
- Source Code (Libraries): https://github.com/psu-libraries
- LinkedIn: https://www.linkedin.com/school/penn-state-university/

## Notes

All entries reflect what could be publicly verified on 2026-06-03. The LionSpaceFIS API was confirmed reachable (HTTP 200 on `/fis-api/health` and `/fis-api/v1/campuses`). The Researcher Metadata Database API is documented per the OpenAPI standard but is license-key gated, so its endpoints were not exercised. The Penn State IT developer portal landing page loads, but each documented service reference redirects to Shibboleth/WebAccess single sign-on and is not publicly viewable. The public LionPATH class search is a UI (not an API) and returned 403 to automated requests. No endpoints or authentication schemes were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
