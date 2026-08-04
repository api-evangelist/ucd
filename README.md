# University College Dublin (ucd)

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

University College Dublin (UCD) is Ireland's largest university and ranks #126 in the QS World University Rankings 2025. This repository catalogs UCD's public, machine-readable developer/API footprint as an APIs.json provider profile. UCD has no central developer portal; its real programmatic surface is concentrated in library and cultural-heritage systems — the UCD Digital Library (IIIF and geospatial data services), the DSpace-based Research Repository UCD (OAI-PMH and REST), and the Dúchas API for the National Folklore Collection.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ucd/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ucd-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Ireland, Library, Digital Library, IIIF, Open Access, Cultural Heritage

## APIs

- **UCD Digital Library Image & Presentation API (IIIF)** — IIIF Image API 2.0 and Presentation API 2.0 for digitized objects and collections. Docs: https://digital.ucd.ie/help/
- **UCD Digital Library Geospatial Data API** — boundary/search geodata for map visualisations, plus an unAPI metadata endpoint. Docs: https://digital.ucd.ie/help/
- **Research Repository UCD (DSpace OAI-PMH / REST)** — open-access publications and theses metadata via OAI-PMH and the DSpace REST API. Docs: https://libguides.ucd.ie/RRU/usage
- **Dúchas API (National Folklore Collection, UCD)** — JSON access to the National Folklore Collection; requires an API key. Docs: https://docs.gaois.ie — Source docs: https://github.com/gaois/DuchasAPI-docs

## Plans / Rate Limits / FinOps

- Plans: [plans/ucd-plans-pricing.yml](plans/ucd-plans-pricing.yml)
- Rate Limits: [rate-limits/ucd-rate-limits.yml](rate-limits/ucd-rate-limits.yml)
- FinOps: [finops/ucd-finops.yml](finops/ucd-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ucd.ie/
- GitHub: https://github.com/University-College-Dublin
- LinkedIn: https://www.linkedin.com/school/university-college-dublin/
- Developer Portal (Digital Library help): https://digital.ucd.ie/help/

## Notes

All entries reflect URLs verified on 2026-06-03; no endpoints were fabricated. The official ucd.ie site returns 403 to scripted requests (bot protection) but resolves in a browser. The Dúchas API base returns HTTP 500 without a key/parameters, confirming it is live but gated. The `data.ucd.ie` host cited as the IIIF/geospatial image base in third-party documentation did not resolve during probing, and `digital.ucd.ie/research/index.php` now returns 404 — IIIF/geospatial services are documented but not all directly reachable from published URLs. UCD offers no unified self-service API program; administrative and identity systems require institutional affiliation.

## Maintainers

- Kin Lane — kin@apievangelist.com
