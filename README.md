# Kyoto University (kyoto)

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
