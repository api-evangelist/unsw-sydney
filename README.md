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

The University of New South Wales (UNSW Sydney) is a public research university in Sydney, Australia, and a member of the Group of Eight. This repository catalogs UNSW's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile, under the **university pipeline** — which settles *who operates* each surface before saving anything, because a university is a federation of buyers and most of what looks like an institutional API is a vendor's contract running under the institution's name.

APIs.json: https://raw.githubusercontent.com/api-evangelist/unsw-sydney/refs/heads/main/apis.yml

Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=unsw-sydney-api-evangelist&utm_content=repo

## Type

- **Class:** university (`x-type: university`)
- **Category:** Public Research University
- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

University, Higher Education, Education, Research, Australia, Group of Eight, Sydney, Research Repository, Identity Federation, Course Catalog, Library, Open Repository

## Surfaces, by operator

Every surface carries an `x-operator`. `institution` means UNSW runs the thing the contract describes; `tenant` means UNSW's data on someone else's platform, which is a real institutional fact but not UNSW's engineering.

### institution

- **UNSWorks Repository REST API (DSpace 7.0)** — `https://unsworks.unsw.edu.au/server/api`. Anonymous service document, communities, collections, metadata registry, entity types and discovery search; item and bitstream browse return 401. Handles under the UNSW prefix 1959.4. OpenAPI derived from live probes: [openapi/unsw-sydney-unsworks-dspace-openapi.yml](openapi/unsw-sydney-unsworks-dspace-openapi.yml)
- **UNSWorks Repository OAI-PMH** — `https://unsworks.unsw.edu.au/oai/request`. OAI-PMH 2.0, fully anonymous, twelve metadata formats, records back to 2007-11-06. [openapi/unsw-sydney-unsworks-oai-pmh-openapi.yml](openapi/unsw-sydney-unsworks-oai-pmh-openapi.yml)
- **UNSW Shibboleth Identity Provider** — `https://aaf.unsw.edu.au/idp/shibboleth`. SAML 2.0 entity metadata published on UNSW's own domain and registered in the Australian Access Federation (an eduGAIN participant). The surface class universities operate by definition and almost nobody catalogues.
- **UNSW Enterprise Developer Portal** — `https://apideveloper.unsw.edu.au/`. Real, live, and completely gated. Catalogued as a statement about the gate, not about the APIs behind it.

### tenant

- **Moodle @ UNSW (TELT)** — a conformant LTI 1.3 platform on a UNSW hostname, operated for UNSW by Open LMS / Learning Technologies Group.
- **UNSW Library discovery** — an Ex Libris Primo VE view (`vid=61UNSW_INST:UNSWS`). No Ex Libris specification is saved under this slug.
- **Freerooms API (DevSoc)** — live student-society campus rooms/buildings API on `devsoc.app`.
- **UNSW Timetable API (DevSoc)** — **archived 2026-04-05**, read-only.
- **UNSW Handbook API (CSESoc)** — **archived 2026-04-03**, read-only.

## Domain standards (Kin Score `education` regime)

Reward-only. A standard is `confirmed` only where a live machine-readable artifact was fetched and read.

| Standard | Status | Operator | Evidence |
|---|---|---|---|
| oai-pmh 2.0 | confirmed | institution | `?verb=Identify` on UNSW's own host |
| saml 2.0 | confirmed | institution | IdP entity metadata, `protocolSupportEnumeration` |
| shibboleth | confirmed | institution | `shibmd:Scope` = `unsw.edu.au`, AAF-registered |
| lti 1.3 | confirmed | tenant | live JWKS at `/mod/lti/certs.php` |
| orcid | not evidenced | — | field registered, no Person entity type, no populated value |
| scim, oneroster, ed-fi, caliper, qti, datacite, crossref | not evidenced | — | — |

Full detail: [conformance/unsw-sydney-education-standards-conformance.yml](conformance/unsw-sydney-education-standards-conformance.yml)

## Artifacts

- OpenAPI: [openapi/](openapi/) (pristine pre-refine copies in [openapi/_original/](openapi/_original/))
- JSON Schema: [json-schema/unsw-sydney-unsworks-dspace-schema.json](json-schema/unsw-sydney-unsworks-dspace-schema.json)
- Examples: [examples/](examples/) — verbatim captured live responses
- Vocabulary: [vocabulary/unsw-sydney-unsworks-vocabulary.yml](vocabulary/unsw-sydney-unsworks-vocabulary.yml)
- Rules: [rules/unsw-sydney-rules.yml](rules/unsw-sydney-rules.yml)
- Authentication: [authentication/unsw-sydney-authentication.yml](authentication/unsw-sydney-authentication.yml)
- Scopes: [scopes/unsw-sydney-scopes.yml](scopes/unsw-sydney-scopes.yml) — recorded absence
- Errors: [errors/unsw-sydney-errors.yml](errors/unsw-sydney-errors.yml)
- Conformance: [conformance/unsw-sydney-education-standards-conformance.yml](conformance/unsw-sydney-education-standards-conformance.yml)
- Lifecycle: [lifecycle/unsw-sydney-lifecycle.yml](lifecycle/unsw-sydney-lifecycle.yml)
- Plans & Pricing: [plans/unsw-sydney-plans-pricing.yml](plans/unsw-sydney-plans-pricing.yml)
- Rate Limits: [rate-limits/unsw-sydney-rate-limits.yml](rate-limits/unsw-sydney-rate-limits.yml)
- FinOps: [finops/unsw-sydney-finops.yml](finops/unsw-sydney-finops.yml)

Every artifact carries `generated`, `method` and `source`. Nothing here is inferred from software documentation — every path, parameter, response and error code was observed in a live response on 2026-08-19.

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.unsw.edu.au/
- Developer Portal: https://apideveloper.unsw.edu.au/
- Research Repository: https://unsworks.unsw.edu.au/
- Identity Federation: https://aaf.unsw.edu.au/idp/shibboleth
- Research Computing (Katana): https://docs.restech.unsw.edu.au/
- Library: https://www.library.unsw.edu.au/
- Course Catalog (Handbook): https://www.handbook.unsw.edu.au/
- AI Policy: https://www.teaching.unsw.edu.au/ai/guidelines
- AI Tooling: https://www.unsw.edu.au/myit/emerging-technologies/ai
- GitHub Organization: https://github.com/unsw-edu-au
- LinkedIn: https://www.linkedin.com/school/unsw/

## Coverage

`gated`. UNSW's one substantial institution-operated API platform cannot be read without authorisation, and authorisation is manual. Everything that could be read was read completely. Nothing was blocked by bot protection. UNSW operates **no open data portal** (`data.unsw.edu.au` redirects to an information-governance page), and publishes no OpenAPI, no status page, no changelog, no `llms.txt` and no `security.txt`. A thin profile here is a correct measurement of UNSW's publishing posture, not a gap in the sweep.

## Notes

Corrections made in the 2026-08-19 re-profile: both community APIs previously listed as live have since been **archived by their owners** and are recorded as such; the GitHub organization pointer moved from the DevSoc student society to UNSW's own `unsw-edu-au` org; the UNSW Shibboleth IdP and the Ex Libris Primo tenancy were found and added; and every surface now carries `x-operator` with the evidence that settled it. `api.unsw.edu.au` returns 502 and is deliberately **not** catalogued as a surface. `resdata.unsw.edu.au` no longer resolves (retired 2021). LinkedIn returns HTTP 999 due to bot-blocking, which grades live, not dead. No endpoints, parameters, or properties were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
