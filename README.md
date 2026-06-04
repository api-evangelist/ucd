# University College Dublin (ucd)

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
