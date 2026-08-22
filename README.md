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

Kyoto University (京都大学) is a national research university in Kyoto, Japan, established in 1897 and ranked #36 in the QS World University Rankings. This repository catalogs its public, machine-readable footprint as an [APIs.json](https://apisjson.org) profile. The university operates no developer portal, no API gateway and no OpenAPI of its own — but it does run four genuinely first-party machine-readable surfaces on its own hosts: the KURENAI research repository (DSpace 7.6 REST + OAI-PMH 2.0), the PandA Learning Support System (Sakai Entity Broker + IMS LTI 1.3 and 1.1), and its own Shibboleth SAML 2.0 identity provider registered in the GakuNin federation.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/kyoto/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=kyoto-api-evangelist&utm_content=repo

## Type

- university (Public Research University)
- Index
- Consumer
- 3rd-Party

## Tags

University, Higher Education, Education, Japan, National University, Research Repository, Research Data, Identity Federation, Learning Management, Open Access, Research Computing, Scholarly

## APIs

Every surface below is `x-operator: institution` — Kyoto University's own host, own network, own engineering. No vendor contract is credited to this institution.

- **KURENAI OAI-PMH API** — OAI-PMH 2.0 harvesting for the Kyoto University Research Information Repository; 15 metadata formats including jpcoar_2.0 and junii2, content back to 2006-06-05. Docs: https://repository.kulib.kyoto-u.ac.jp/ — Base: `https://repository.kulib.kyoto-u.ac.jp/server/oai/request`
- **KURENAI DSpace REST API** — DSpace 7.6 HAL+JSON, anonymous reads on the root, communities and collections. Base: `https://repository.kulib.kyoto-u.ac.jp/server/api`
- **PandA Learning Support System API (Sakai Entity Broker + IMS LTI)** — 53 registered entity prefixes, a fully public 96-entry tool registry, an LTI 1.3 platform JWKS and a live LTI 1.1 Basic Outcomes service. Docs: https://www.iimc.kyoto-u.ac.jp/en/services/education/lms — Base: `https://panda.ecs.kyoto-u.ac.jp`
- **Kyoto University Shibboleth Identity Provider (GakuNin)** — public SAML 2.0 metadata, scope `kyoto-u.ac.jp`, registered in GakuNin (NII) and thereby eduGAIN. Base: `https://authidp1.iimc.kyoto-u.ac.jp/idp/shibboleth`

## Education-regime conformance

Five of the twelve Kin Score `education` regime standards are met with live evidence, all first-party: **oai-pmh**, **shibboleth**, **saml**, **lti** (1.3 + 1.1) and **orcid**. Not found: scim, oneroster, ed-fi, caliper, qti, datacite, crossref. See [conformance/kyoto-education-standards-conformance.yml](conformance/kyoto-education-standards-conformance.yml).

## Artifacts

- [conformance/kyoto-education-standards-conformance.yml](conformance/kyoto-education-standards-conformance.yml)
- [authentication/kyoto-authentication.yml](authentication/kyoto-authentication.yml) · [authentication/kyoto-saml-idp-metadata.xml](authentication/kyoto-saml-idp-metadata.xml)
- [errors/kyoto-errors.yml](errors/kyoto-errors.yml)
- [scopes/kyoto-scopes.yml](scopes/kyoto-scopes.yml)
- [lifecycle/kyoto-lifecycle.yml](lifecycle/kyoto-lifecycle.yml)
- [plans/kyoto-plans-pricing.yml](plans/kyoto-plans-pricing.yml)
- [rate-limits/kyoto-rate-limits.yml](rate-limits/kyoto-rate-limits.yml)
- [finops/kyoto-finops.yml](finops/kyoto-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.kyoto-u.ac.jp/en
- Research repository: https://repository.kulib.kyoto-u.ac.jp/
- Identity federation: https://authidp1.iimc.kyoto-u.ac.jp/idp/shibboleth
- Learning (PandA): https://www.iimc.kyoto-u.ac.jp/en/services/education/lms
- Research computing: https://www.iimc.kyoto-u.ac.jp/en/services/comp
- Library catalog (KULINE): https://kuline.kulib.kyoto-u.ac.jp/opac/opac_search/
- Researcher database (KDB): https://kdb.iimc.kyoto-u.ac.jp/
- AI tooling: https://www.iimc.kyoto-u.ac.jp/en/services/gen-ai
- GitHub: https://github.com/kyoto-u
- LinkedIn: https://www.linkedin.com/school/kyoto-university/
- X: https://x.com/KyotoU_News

## Notes

Re-profiled 2026-08-19 under the API Evangelist university pipeline, which settles **who operates each surface** before saving any contract. Every endpoint here was probed live on that date with no credentials.

Two surfaces were newly discovered and had been entirely absent from the June 2026 profile: the **PandA (Sakai) LMS**, which is a live IMS LTI 1.3 platform, and the **Shibboleth/GakuNin SAML metadata** endpoint. One recorded fact was wrong and was corrected: the DSpace REST API's base URL pointed at the OAI-PMH path.

Several things that look like surfaces are not, and are recorded as such rather than credited: `repository.kulib.kyoto-u.ac.jp` returns HTTP 200 with an Angular shell for paths that do not exist, so its `/.well-known/security.txt` and `/feed/rss_2.0/site` are **soft-404s**, not a security contact and not a feed. `kyoto-u.figshare.com` is **wildcard DNS**, not a Figshare tenancy — a nonsense control subdomain returns the identical HTTP 202 with a zero-length body. The IIMC ORCID service and the university's Generative AI portal are **gated**, not absent. The old researcher database host serves only a notice that it moved in 2022. The dead `@Kyoto_Univ_PR` handle was removed; the official account is `@KyotoU_News`. The LinkedIn page returns HTTP 999 from LinkedIn's bot challenge — blocked, not dead.

Student information, course registration and timetable systems are behind campus accounts and are not public APIs. None are invented here.

## Maintainers

- Kin Lane — kin@apievangelist.com
