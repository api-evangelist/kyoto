# Kyoto University

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

Kyoto University (京都大学) is a national research university in Kyoto, Japan, established in 1897 and ranked #36 in the QS World University Rankings. It operates no developer portal, no API gateway, no API terms of service and no OpenAPI of its own, and this profile records that plainly. What it does run, on its own hosts and its own network, is a small set of genuinely institution-operated machine-readable surfaces: KURENAI, the Kyoto University Research Information Repository, a self-hosted DSpace 7.6 with an anonymous HAL+JSON REST API and an OAI-PMH 2.0 endpoint serving 15 metadata formats including JPCOAR and junii2, holding content back to 2006; PandA, the university's Sakai Learning Support System, whose Entity Broker answers JSON on 53 registered entity prefixes and which is a live IMS LTI 1.3 platform publishing its own signing keyset alongside a working LTI 1.1 outcomes service; and its own Shibboleth SAML 2.0 identity provider, registered in GakuNin, the Japanese academic federation, which participates in eduGAIN. Those surfaces sit on hosts inside 133.3.0.0/16, registered by JPNIC to Kyoto University as KUINS, or in the university's own AWS account. Five of the twelve Kin Score education-regime standards are met with live evidence — oai-pmh, shibboleth, saml, lti and orcid — which is unusual for this cohort and entirely first-party. Everything else is a human-facing service: the KULINE library catalogue, the KDB researcher database, OpenCourseWare, and the generative-AI tooling the IIMC brokers from Google and Microsoft. Student information, course registration and timetable systems are behind campus accounts and are not public APIs.

**Areas:** University · Higher Education · Education · Japan · National University · Research Repository · Research Data · Identity Federation · LMS · Open Access · Research Computing · Scholarly

## Kyoto University on APIs.io

Everything profiled for Kyoto University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kyoto/](https://apis.io/providers/kyoto/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [KURENAI OAI-PMH API](https://apis.io/apis/kyoto/kyoto-oai-pmh-api/) — OAI-PMH 2.0 metadata harvesting interface for KURENAI, the Kyoto University Research Information Repository. Anonymous, verb-driven, and serving 15 metadata…
- [KURENAI DSpace REST API](https://apis.io/apis/kyoto/kyoto-rest-api/) — The DSpace 7.6 HAL+JSON REST API of the Kyoto University Research Information Repository. The root document at /server/api advertises every endpoint as HAL…
- [PandA Learning Support System API (Sakai Entity Broker + IMS LTI)](https://apis.io/apis/kyoto/kyoto-lms-api/) — PandA is the Kyoto University Learning Support System, a Sakai deployment operated by the Institute for Information Management and Communication and…
- [Kyoto University Shibboleth Identity Provider (GakuNin)](https://apis.io/apis/kyoto/sso/) — Kyoto University operates its own Shibboleth SAML 2.0 identity provider, run by the Institute for Information Management and Communication, with public…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Kyoto Agentic Access](https://apis.io/agentic-access/kyoto/kyoto-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [KURENAI Collection](https://apis.io/schemas/kyoto/kyoto-collection/)
- [KURENAI Community](https://apis.io/schemas/kyoto/kyoto-community/)
- [PandA Entity Broker Collection](https://apis.io/schemas/kyoto/kyoto-panda-entity-collection/)
- [PandA Tool](https://apis.io/schemas/kyoto/kyoto-panda-tool/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Kyoto Collection Structure](https://apis.io/json-structure/kyoto/kyoto-collection-structure/)
- [Kyoto Community Structure](https://apis.io/json-structure/kyoto/kyoto-community-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Kyoto Context](https://apis.io/jsonld/kyoto/kyoto-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [KURENAI Repository Vocabulary](https://apis.io/vocabularies/kyoto/kyoto-vocabulary/)

#### Examples (6)

Example requests and responses.

- [Kyoto Getroot Example](https://apis.io/examples/kyoto/kyoto-getRoot-example/)
- [Kyoto Listcommunities Example](https://apis.io/examples/kyoto/kyoto-listCommunities-example/)
- [Kyoto Lti13 Keyset Example](https://apis.io/examples/kyoto/kyoto-lti13-keyset-example/)
- [Kyoto Oaiidentify Example](https://apis.io/examples/kyoto/kyoto-oaiIdentify-example/)
- [Kyoto Panda Session Example](https://apis.io/examples/kyoto/kyoto-panda-session-example/)
- [Kyoto Panda Tool Example](https://apis.io/examples/kyoto/kyoto-panda-tool-example/)

#### Collections (2)

Postman and Open Collection request collections.

- [KURENAI Repository API (DSpace 7.6 REST + ) OAI-PMH API](https://apis.io/collections/kyoto/open-kyoto-oai-pmh-api/)
- [KURENAI Repository API (DSpace 7.6 + ) OAI-PMH REST API](https://apis.io/collections/kyoto/open-kyoto-rest-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Kyoto University — jsonschema rules](https://apis.io/rules/kyoto/kyoto-jsonschema-spectral-rules/)
- [Kyoto University API Rules](https://apis.io/rules/kyoto/kyoto-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Kyoto Authentication](https://apis.io/security/kyoto/kyoto-authentication/)
- [Kyoto Domain Security](https://apis.io/security/kyoto/kyoto-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Kyoto Scopes](https://apis.io/scopes/kyoto/kyoto-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Kyoto Plans Pricing](https://apis.io/plans/kyoto/kyoto-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Kyoto Rate Limits](https://apis.io/rate-limits/kyoto/kyoto-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Kyoto Finops](https://apis.io/finops/kyoto/kyoto-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.kyoto-u.ac.jp/en)
- [Documentation](https://www.iimc.kyoto-u.ac.jp/en/services)
- [Support](https://www.kyoto-u.ac.jp/en/contact)
- [Terms of service](https://www.kyoto-u.ac.jp/en/site-policy)
- [Privacy policy](https://www.kyoto-u.ac.jp/en/privacy-policy)

## API Evangelist rating

**Kin Score 37.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 58.0 |
| Contract governance | 17.4 |
| Operational transparency | 10.5 |
| Developer ergonomics | 26.2 |
| Access clarity | 26.3 |

**Agent readiness 22.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
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

**Regulatory alignment 34.3** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/kyoto/](https://apis.io/providers/kyoto/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Kyoto University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kyoto/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
