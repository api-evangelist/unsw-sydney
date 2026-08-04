# University of New South Wales (unsw-sydney)

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

The University of New South Wales (UNSW Sydney) is a public research university in Sydney, Australia, ranked #35 in the QS World University Rankings 2025. This repository catalogs UNSW's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile. UNSW runs a gated Enterprise Developer Portal on Microsoft Azure API Management, alongside a publicly accessible institutional research repository (UNSWorks / DSpace) and several community-maintained student-society APIs.

APIs.json: https://raw.githubusercontent.com/api-evangelist/unsw-sydney/refs/heads/main/apis.yml

Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=unsw-sydney-api-evangelist&utm_content=repo

## Type

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Repository, Australia, Sydney

## APIs

- **UNSW Enterprise Developer Portal** — Azure API Management portal exposing gated enterprise APIs (student data, campus services). Docs: https://apideveloper.unsw.edu.au/getting-started
- **UNSWorks Repository REST API (DSpace)** — DSpace 7.0 REST/HAL API for the institutional research repository. Docs: https://unsworks.unsw.edu.au/server/api
- **UNSWorks Repository OAI-PMH** — OAI-PMH 2.0 metadata harvesting endpoint. Docs: https://unsworks.unsw.edu.au/oai/request?verb=Identify
- **UNSW Timetable API (community)** — DevSoc-maintained scraper/API for the UNSW timetable (unofficial). Docs: https://github.com/devsoc-unsw/timetable-scraper
- **UNSW Handbook API (community)** — CSESoc-maintained API for UNSW Handbook course/degree data (unofficial). Docs: https://github.com/csesoc/handbook-api

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/unsw-sydney-plans-pricing.yml](plans/unsw-sydney-plans-pricing.yml)
- Rate Limits: [rate-limits/unsw-sydney-rate-limits.yml](rate-limits/unsw-sydney-rate-limits.yml)
- FinOps: [finops/unsw-sydney-finops.yml](finops/unsw-sydney-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.unsw.edu.au/
- Developer Portal: https://apideveloper.unsw.edu.au/
- LinkedIn: https://www.linkedin.com/school/unsw/
- GitHub (community / DevSoc): https://github.com/devsoc-unsw

## Notes

All endpoints were probed during cataloging. The UNSW Enterprise Developer Portal is real but **gated** — onboarding is request-based and no public API base URLs or endpoints are disclosed, so individual enterprise APIs could not be enumerated or exercised. The UNSWorks DSpace REST API and OAI-PMH endpoint were verified live (HTTP 200, valid JSON/XML). Timetable and Handbook programmatic access is **community-maintained** by UNSW student societies (DevSoc, CSESoc), not official UNSW-operated APIs. The `github.com/unsw` org is dormant (a single 2014 test repo) and is not used as the primary GitHub reference. LinkedIn returns HTTP 999 due to bot-blocking, not because the page is missing. No endpoints, parameters, or properties were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
