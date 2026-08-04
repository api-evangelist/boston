# Boston University (boston)

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

Boston University is a private research university in Boston, Massachusetts (chartered 1869), ranked #88 in the QS World University Rankings 2025. This repository catalogs its public developer/API footprint as an [APIs.json](https://apisjson.org) profile. BU's openly machine-readable surface is modest: the OpenBU institutional repository exposes a live OAI-PMH endpoint, while other API surfaces (an internal WEB APIs portal and AI/LLM API key access) are gated.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/boston/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=boston-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Open Data, United States

## APIs

- **OpenBU Repository OAI-PMH API** — Public OAI-PMH 2.0 metadata-harvesting endpoint for BU Libraries' DSpace institutional repository. Docs: https://open.bu.edu/ — Base URL: `https://open.bu.edu/server/oai/request`
- **AI API Access (Azure OpenAI / Amazon Bedrock)** — Gated LLM API key brokering via IS&T (faculty/researchers/staff only; request form required). Docs: https://www.bu.edu/tech/services/cccs/collaboration/conversational-ai/ai-api-access/

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/boston-plans-pricing.yml](plans/boston-plans-pricing.yml)
- Rate Limits: [rate-limits/boston-rate-limits.yml](rate-limits/boston-rate-limits.yml)
- FinOps: [finops/boston-finops.yml](finops/boston-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.bu.edu/
- GitHub: https://github.com/bu-ist
- LinkedIn: https://www.linkedin.com/school/boston-university/
- Review: [review.yml](review.yml)

## Notes

All entries reflect URLs probed on 2026-06-03; no endpoints were fabricated. The OpenBU OAI-PMH endpoint was verified live (HTTP 200, valid Identify response). The referenced internal API portal at webapi.bu.edu does not resolve from off-network (NXDOMAIN / connection refused) and is treated as gated. The AI API access path is gated behind an approval form with no public base URL. The bu-ist GitHub organization hosts WordPress/web tooling rather than open API specifications.

## Maintainers

- Kin Lane — kin@apievangelist.com
