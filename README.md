# University of New South Wales

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

The University of New South Wales (UNSW Sydney) is a public research university in Sydney, Australia, and a member of the Group of Eight. Like almost every institution, UNSW is a federation of buyers rather than an API producer, and its programmable footprint has to be read that way. The one substantial platform UNSW runs itself — the Enterprise API Gateway and Developer Portal on Microsoft Azure API Management at apideveloper.unsw.edu.au — is completely gated: onboarding is request-based, the API catalogue is invisible before sign-in, no base URL is disclosed, and the portal states outright that consumers cannot exercise APIs in the portal. The surfaces a member of the public can actually read are three, and all three are institution- operated: the UNSWorks institutional repository REST API (DSpace 7.0, anonymous discovery search, authenticated item browse), its OAI-PMH 2.0 harvesting endpoint exposing twelve metadata formats back to 2007, and the UNSW Shibboleth identity provider whose SAML 2.0 entity metadata is published under the institution's own domain and registered in the Australian Access Federation. Everything else is a tenancy on someone else's platform — an Ex Libris Primo library discovery view, a vendor-hosted Moodle that is a conformant LTI 1.3 platform, a Microsoft Power Apps research-data toolkit — or student-society work on non-institution domains. UNSW publishes no OpenAPI, no open data portal, no status page, no changelog and no API governance ruleset.

**Areas:** University · Higher Education · Education · Research · Australia · Group of Eight · Sydney · Research Repository · Identity Federation · Course Catalog · Library · Open Repository

## University of New South Wales on APIs.io

Everything profiled for University of New South Wales is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/unsw-sydney/](https://apis.io/providers/unsw-sydney/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [UNSW Shibboleth Identity Provider (AAF / eduGAIN)](https://apis.io/apis/unsw-sydney/shibboleth-idp/) — UNSW's own SAML 2.0 identity provider — a Shibboleth IdP whose entity metadata is published as a machine-readable XML document at the entityID URL and is…
- [UNSW Enterprise Developer Portal](https://apis.io/apis/unsw-sydney/developer-portal/) — The front door to UNSW's Enterprise API Gateway, built on Microsoft Azure API Management. Cataloguing it is a statement about the gate, not about the APIs…
- [Moodle @ UNSW (TELT) — LTI 1.3 platform](https://apis.io/apis/unsw-sydney/moodle-lti/) — UNSW's learning management system, operated for UNSW by Open LMS. It is a live, conformant 1EdTech LTI 1.3 platform: the public keyset at /mod/lti/certs.php…
- [UNSW Library discovery (Ex Libris Primo VE)](https://apis.io/apis/unsw-sydney/primo-discovery/) — UNSW Library's discovery layer runs on Ex Libris Primo VE. This entry records the tenancy so the relationship is visible in the catalogue; no Ex Libris…
- [Freerooms API (DevSoc, community)](https://apis.io/apis/unsw-sydney/freerooms/) — A live student-society API exposing UNSW campus buildings and teaching rooms with coordinates, capacity, school and usage type — the campus-life surface…
- [UNSW Timetable API (DevSoc, community) — ARCHIVED](https://apis.io/apis/unsw-sydney/timetable-scraper/) — A scraper and public API for UNSW's timetable site, produced by the UNSW Software Development Society. ARCHIVED BY ITS OWNER ON 2026-04-05 and now…
- [UNSW Handbook API (CSESoc, community) — ARCHIVED](https://apis.io/apis/unsw-sydney/handbook-api/) — A public API for fetching degree, specialisation and course information from the UNSW Handbook, published by the UNSW Computer Science and Engineering…
- [University of New South Wales Core API](https://apis.io/apis/unsw-sydney/unsw-sydney-core-api/) — Communities, collections, sites and the metadata registry.
- [University of New South Wales Discover API](https://apis.io/apis/unsw-sydney/unsw-sydney-discover-api/) — Public discovery search over repository objects.
- [University of New South Wales Oai Pmh API](https://apis.io/apis/unsw-sydney/unsw-sydney-oai-pmh-api/) — OAI-PMH 2.0 verbs, all exercised live against this endpoint.
- [University of New South Wales Root API](https://apis.io/apis/unsw-sydney/unsw-sydney-root-api/) — Service entry point and HAL link index.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (1)

The data models the API reads and writes.

- [UNSWorks Repository DSpace 7.0 REST payloads](https://apis.io/schemas/unsw-sydney/unsw-sydney-unsworks-dspace/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Unsw Sydney Context](https://apis.io/jsonld/unsw-sydney/unsw-sydney-context/)

#### Examples (2)

Example requests and responses.

- [Unsw Sydney Moodle Lti Jwks Example](https://apis.io/examples/unsw-sydney/unsw-sydney-moodle-lti-jwks-example/)
- [Unsw Sydney Unsworks Dspace Example](https://apis.io/examples/unsw-sydney/unsw-sydney-unsworks-dspace-example/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [University of New South Wales API Rules](https://apis.io/rules/unsw-sydney/unsw-sydney-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Unsw Sydney Authentication](https://apis.io/security/unsw-sydney/unsw-sydney-authentication/)
- [Unsw Sydney Domain Security](https://apis.io/security/unsw-sydney/unsw-sydney-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Unsw Sydney Scopes](https://apis.io/scopes/unsw-sydney/unsw-sydney-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Unsw Sydney Plans Pricing](https://apis.io/plans/unsw-sydney/unsw-sydney-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Unsw Sydney Rate Limits](https://apis.io/rate-limits/unsw-sydney/unsw-sydney-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Unsw Sydney Finops](https://apis.io/finops/unsw-sydney/unsw-sydney-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.unsw.edu.au/)
- [Documentation](https://apideveloper.unsw.edu.au/getting-started)
- [Support](https://www.unsw.edu.au/myit)
- [Blog](https://www.unsw.edu.au/newsroom)
- [Terms of service](https://www.unsw.edu.au/copyright-disclaimer)
- [Privacy policy](https://www.unsw.edu.au/privacy)
- [GitHub](https://github.com/unsw-edu-au)

## API Evangelist rating

**Kin Score 40.4** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 55.8 |
| Contract governance | 15.2 |
| Operational transparency | 7.9 |
| Developer ergonomics | 38.1 |
| Access clarity | 39.5 |

**Agent readiness 32.8** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 34.3** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/unsw-sydney/](https://apis.io/providers/unsw-sydney/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of New South Wales: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/unsw-sydney/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
