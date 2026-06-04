# University of New South Wales (unsw-sydney)

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
