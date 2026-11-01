# University College Dublin

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

University College Dublin is Ireland's largest university, a public research institution in Belfield, Dublin. It operates no API programme: there is no developer portal, no API key issuance, no OAuth authorization server and no first-party OpenAPI anywhere on a ucd.ie host. What it does operate, verified live on 2026-08-30, is three real machine-readable surfaces — an OAI-PMH 2.0 harvesting endpoint for Research Repository UCD (17,167 records, fourteen metadata formats, plus an OpenAIRE CRIS base URL), a SAML 2.0 Shibboleth Identity Provider registered in Edugate/eduGAIN as https://sso.ucd.ie/idp/shibboleth with scope ucd.ie, and static Dublin Core collection data exports from the UCD Digital Library. Everything else is somebody else's engineering under UCD's name: the repository platform is DSpace-CRIS hosted by 4Science, library discovery is Serials Solutions, and the Dúchas API for the National Folklore Collection — the collection is UCD's, the platform is DCU's — was withdrawn by its operator and now returns HTTP 500 on every path. This profile was re-run under the university pipeline on 2026-08-30 and the previously catalogued Dúchas contracts were removed.

**Areas:** University · Higher Education · Education · Ireland · Europe · Public Research University · Research Repository · Open Access · OAI-PMH · Identity Federation · Cultural Heritage · Open Data

## University College Dublin on APIs.io

Everything profiled for University College Dublin is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ucd/](https://apis.io/providers/ucd/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [University College Dublin Identity Provider (Shibboleth / Edugate / eduGAIN)](https://apis.io/apis/ucd/identity-federation/) — UCD's SAML 2.0 Shibboleth Identity Provider, and the institution's only authentication surface it runs itself. It is machine-readable by definition — a…
- [UCD Digital Library collection data exports](https://apis.io/apis/ucd/digital-library-data/) — Static, keyless Dublin Core metadata exports for UCD Library's digital cultural-heritage collections — metadata as CSV and JSON, plus facets, subjects and a…
- [Research Repository UCD — DSpace-CRIS REST API (4Science)](https://apis.io/apis/ucd/dspace-rest/) — A live DSpace-CRIS 7.6.1 HAL REST API on UCD's branded repository host, advertising roughly ninety link relations including items, collections, communities,…
- [Dúchas API — National Folklore Collection (operated by DCU)](https://apis.io/apis/ucd/duchas/) — The National Folklore Collection (Cnuasach Bhéaloideas Éireann) is held at UCD; the Dúchas digitisation platform and its API are built and operated by DCU's…
- [UCD Library discovery (Serials Solutions / Clarivate)](https://apis.io/apis/ucd/library-discovery/) — UCD Library's discovery layer runs on Serials Solutions (Clarivate/ProQuest) under a customer key, not on a UCD host. It exposes a search interface for…
- [University College Dublin OAI PMH API](https://apis.io/apis/ucd/ucd-oai-pmh-api/) — OAI-PMH 2.0 harvesting verbs.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Vocabulary (1)

The provider's domain terms, defined.

- [Duchas API Vocabulary (UCD)](https://apis.io/vocabularies/ucd/ucd-vocabulary/)

#### Examples (1)

Example requests and responses.

- [Ucd Digital Library Facets Example](https://apis.io/examples/ucd/ucd-digital-library-facets-example/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ucd Authentication](https://apis.io/security/ucd/ucd-authentication/)
- [Ucd Domain Security](https://apis.io/security/ucd/ucd-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ucd Plans Pricing](https://apis.io/plans/ucd/ucd-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ucd Rate Limits](https://apis.io/rate-limits/ucd/ucd-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ucd Finops](https://apis.io/finops/ucd/ucd-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ucd.ie/)
- [Documentation](https://libguides.ucd.ie/RRU/usage)
- [Support](https://www.ucd.ie/itservices/ourservices/researchit/)
- [Blog](https://www.ucd.ie/newsandopinion/)
- [Terms of service](https://www.ucd.ie/legal/)
- [Privacy policy](https://www.ucd.ie/privacy/)
- [GitHub](https://github.com/University-College-Dublin)

## API Evangelist rating

**Kin Score 32.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 47.6 |
| Contract governance | 13.6 |
| Operational transparency | 7.9 |
| Developer ergonomics | 28.6 |
| Access clarity | 26.3 |

**Agent readiness 24.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
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

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ucd/](https://apis.io/providers/ucd/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University College Dublin: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ucd/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
