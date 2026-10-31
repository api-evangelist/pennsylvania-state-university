# Pennsylvania State University

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Pennsylvania State University (Penn State) is a public, land-grant research university with its primary campus at University Park, PA, and is ranked #69 in the QS World University Rankings 2025. Its programmable footprint is real but narrow, and it lives almost entirely in University Libraries rather than in central IT. Penn State publishes two genuine first-party OpenAPI descriptions of services it builds and operates itself: the Researcher Metadata Database (RMD), the authority on faculty and research metadata, and ScholarSphere, its self-built institutional repository — both key-gated, both described in OpenAPI 3.0 by the Libraries team that wrote them. Alongside those it runs an open OAI-PMH 2.0 provider over the Electronic Theses and Dissertations Archive, an unauthenticated facilities API from the Office of Physical Plant (LionSpaceFIS), and its own Shibboleth identity provider registered in InCommon. Penn State also authors open-source identity software, including a SCIM 2.0 server implementation. What it no longer has is a central developer portal: docs.developer.psu.edu, which catalogued internal REST services such as PSU ID, Academic Course and Cornerstone behind WebAccess single sign-on, now redirects to sites.psu.edu and has been decommissioned. There is no unified API gateway, no shared credential, and no self-service onboarding — each surface issues its own key out of the unit that operates it.

**Areas:** Education · Higher Education · University · Public Research University · Land Grant · Big Ten · Research · Research Data · Research Repository · Open Access · Identity Federation · Library

## Pennsylvania State University on APIs.io

Everything profiled for Pennsylvania State University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/pennsylvania-state-university/](https://apis.io/providers/pennsylvania-state-university/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [ETDA OAI-PMH Provider](https://apis.io/apis/pennsylvania-state-university/etda-oai-pmh/) — An open OAI-PMH 2.0 harvesting endpoint over Penn State's Electronic Theses and Dissertations Archive, served by the Libraries' own etda_explore application…
- [Penn State Identity Federation (InCommon / Shibboleth)](https://apis.io/apis/pennsylvania-state-university/identity-federation/) — Penn State operates its own Shibboleth identity provider and registers it in the InCommon federation under entityID urn:mace:incommon:psu.edu. Penn State…
- [Pennsylvania State University Buildings API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-buildings-api/) — University buildings and their facility attributes. One tag of the Office of Physical Plant's single LionSpaceFIS service; the buildings, campuses, rooms,…
- [Pennsylvania State University Campuses API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-campuses-api/) — Penn State campus reference data, from the Office of Physical Plant LionSpaceFIS service.
- [Pennsylvania State University Events API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-events-api/) — Change events for buildings and rooms, from the Office of Physical Plant LionSpaceFIS service.
- [Pennsylvania State University Health API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-health-api/) — Service health and status for the LionSpaceFIS facilities service; returns appVersion and appStatus with a database connectivity check. Unauthenticated and…
- [Pennsylvania State University Rooms API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-rooms-api/) — Rooms within buildings, from the Office of Physical Plant LionSpaceFIS service.
- [Pennsylvania State University Collections API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-collections-api/) — The Collections API from Pennsylvania State University — 1 operation(s) for collections.
- [Pennsylvania State University Dois API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-dois-api/) — The Dois API from Pennsylvania State University — 2 operation(s) for dois.
- [Pennsylvania State University Featured Resources API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-featured-resources-api/) — The Featured Resources API from Pennsylvania State University — 1 operation(s) for featured resources.
- [Pennsylvania State University Files API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-files-api/) — The Files API from Pennsylvania State University — 1 operation(s) for files.
- [Pennsylvania State University Ingest API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-ingest-api/) — The Ingest API from Pennsylvania State University — 1 operation(s) for ingest.
- [Pennsylvania State University Organization API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-organization-api/) — The organization API from Pennsylvania State University — 2 operation(s) for organization.
- [Pennsylvania State University Publication API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-publication-api/) — The publication API from Pennsylvania State University — 3 operation(s) for publication.
- [Pennsylvania State University Uploads API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-uploads-api/) — The Uploads API from Pennsylvania State University — 1 operation(s) for uploads.
- [Pennsylvania State University User API](https://apis.io/apis/pennsylvania-state-university/pennsylvania-state-university-user-api/) — The user API from Pennsylvania State University — 9 operation(s) for user.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Pennsylvania State University Agentic Access](https://apis.io/agentic-access/pennsylvania-state-university/pennsylvania-state-university-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Building](https://apis.io/schemas/pennsylvania-state-university/pennsylvania-state-university-building/)
- [Room](https://apis.io/schemas/pennsylvania-state-university/pennsylvania-state-university-room/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Pennsylvania State University Building Structure](https://apis.io/json-structure/pennsylvania-state-university/pennsylvania-state-university-building-structure/)
- [Pennsylvania State University Room Structure](https://apis.io/json-structure/pennsylvania-state-university/pennsylvania-state-university-room-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Pennsylvania State University Context](https://apis.io/jsonld/pennsylvania-state-university/pennsylvania-state-university-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Penn State LionSpaceFIS Facilities Vocabulary](https://apis.io/vocabularies/pennsylvania-state-university/pennsylvania-state-university-vocabulary/)

#### Examples (6)

Example requests and responses.

- [Pennsylvania State University Gethealth Example](https://apis.io/examples/pennsylvania-state-university/pennsylvania-state-university-getHealth-example/)
- [Pennsylvania State University Listbuildings Example](https://apis.io/examples/pennsylvania-state-university/pennsylvania-state-university-listBuildings-example/)
- [Pennsylvania State University Listcampuses Example](https://apis.io/examples/pennsylvania-state-university/pennsylvania-state-university-listCampuses-example/)
- [Pennsylvania State University Listrooms Example](https://apis.io/examples/pennsylvania-state-university/pennsylvania-state-university-listRooms-example/)
- [Pennsylvania State University Rmd Unauthenticated Example](https://apis.io/examples/pennsylvania-state-university/pennsylvania-state-university-rmd-unauthenticated-example/)
- [Pennsylvania State University Scholarsphere Unauthenticated Example](https://apis.io/examples/pennsylvania-state-university/pennsylvania-state-university-scholarsphere-unauthenticated-example/)

#### Collections (5)

Postman and Open Collection request collections.

- [LionSpaceFIS REST Buildings API](https://apis.io/collections/pennsylvania-state-university/open-pennsylvania-state-university-buildings-api/)
- [LionSpaceFIS REST Buildings Campuses API](https://apis.io/collections/pennsylvania-state-university/open-pennsylvania-state-university-campuses-api/)
- [LionSpaceFIS REST Buildings Events API](https://apis.io/collections/pennsylvania-state-university/open-pennsylvania-state-university-events-api/)
- [LionSpaceFIS REST Buildings Health API](https://apis.io/collections/pennsylvania-state-university/open-pennsylvania-state-university-health-api/)
- [LionSpaceFIS REST Buildings Rooms API](https://apis.io/collections/pennsylvania-state-university/open-pennsylvania-state-university-rooms-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Pennsylvania State University — jsonschema rules](https://apis.io/rules/pennsylvania-state-university/pennsylvania-state-university-jsonschema-spectral-rules/)
- [Pennsylvania State University API Rules](https://apis.io/rules/pennsylvania-state-university/pennsylvania-state-university-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Pennsylvania State University Authentication](https://apis.io/security/pennsylvania-state-university/pennsylvania-state-university-authentication/)
- [Pennsylvania State University Domain Security](https://apis.io/security/pennsylvania-state-university/pennsylvania-state-university-domain-security/)
- [Pennsylvania State University Trust Center](https://apis.io/security/pennsylvania-state-university/pennsylvania-state-university-trust-center/)
- [Pennsylvania State University Vulnerability Disclosure](https://apis.io/security/pennsylvania-state-university/pennsylvania-state-university-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Pennsylvania State University Plans Pricing](https://apis.io/plans/pennsylvania-state-university/pennsylvania-state-university-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Pennsylvania State University Rate Limits](https://apis.io/rate-limits/pennsylvania-state-university/pennsylvania-state-university-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Pennsylvania State University Finops](https://apis.io/finops/pennsylvania-state-university/pennsylvania-state-university-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.psu.edu/)
- [Documentation](https://docs.scholarsphere.psu.edu/)
- [API reference](https://metadata.libraries.psu.edu/api_docs)
- [Blog](https://www.psu.edu/news)
- [Privacy policy](https://www.psu.edu/web-privacy-statement)
- [GitHub](https://github.com/PennState)

## API Evangelist rating

**Kin Score 46.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 57.3 |
| Contract governance | 18.2 |
| Operational transparency | 18.4 |
| Developer ergonomics | 38.1 |
| Access clarity | 47.4 |

**Agent readiness 26.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 43.1** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/pennsylvania-state-university/](https://apis.io/providers/pennsylvania-state-university/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Pennsylvania State University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/pennsylvania-state-university/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
