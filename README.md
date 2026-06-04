# Kyoto University (kyoto)

Kyoto University is a national research university in Kyoto, Japan, ranked #37 in the QS World University Rankings 2025. This repository catalogs its public, machine-readable developer and API footprint as an [APIs.json](https://apisjson.org) profile. The university does not operate a centralized developer portal; its confirmed public surfaces are scholarly and open-source infrastructure — the KURENAI research repository OAI-PMH endpoint, the kyoto-u GitHub organization, and the IIMC Shibboleth/SAML authentication system.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/kyoto/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=kyoto-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Scholarly, Repository, Japan

## APIs

- **KURENAI OAI-PMH Metadata API** — DSpace-based research information repository metadata harvesting (OAI-PMH 2.0). Docs: https://repository.kulib.kyoto-u.ac.jp/ — Base: `https://repository.kulib.kyoto-u.ac.jp/server/oai/request`
- **Kyoto University Integrated Authentication (Shibboleth/SAML)** — IIMC-operated SAML identity provider for SPS-ID/ECS-ID accounts (gated, committee-approved federation). Docs: https://www.iimc.kyoto-u.ac.jp/en/services/account/auth-system

## Plans

- [plans/kyoto-plans-pricing.yml](plans/kyoto-plans-pricing.yml)

## Rate Limits

- [rate-limits/kyoto-rate-limits.yml](rate-limits/kyoto-rate-limits.yml)

## FinOps

- [finops/kyoto-finops.yml](finops/kyoto-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.kyoto-u.ac.jp/en
- GitHub: https://github.com/kyoto-u
- LinkedIn: https://www.linkedin.com/school/kyoto-university/
- Twitter: https://twitter.com/Kyoto_Univ_PR
- Authentication: https://www.iimc.kyoto-u.ac.jp/en/services/account/auth-system

## Notes

All endpoints were probed live on 2026-06-03. The KURENAI OAI-PMH endpoint was verified with an `Identify` request returning repositoryName "Kyoto University Research Information Repository" (protocolVersion 2.0). The kyoto-u GitHub organization was confirmed ("Kyoto University Open Source Project", ~20 repos). Student information, course, catalog, and timetable systems are gated behind campus accounts and are not publicly documented APIs — none are invented here. The LinkedIn page returns HTTP 999 due to LinkedIn bot-blocking, not absence.

## Maintainers

- Kin Lane — kin@apievangelist.com
