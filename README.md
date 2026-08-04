# Pennsylvania State University (pennsylvania-state-university)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
