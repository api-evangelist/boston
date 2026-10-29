# Boston University

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

Boston University is a private research university in Boston, Massachusetts, chartered in 1869, serving roughly 37,000 students across three campuses. Like most universities it is a federation of buyers rather than an API producer, and its programmable footprint has to be read that way. The one substantial machine-readable interface Boston University both operates AND authors is the WordPress REST API on www.bu.edu: nine of its fifteen namespaces are BU IS&T's own plugins — bu-alert, bu-blocks, bu-navigation, bu-slideshow, bu-tts and others — open-sourced at github.com/bu-ist and documented at developer.bu.edu, with some routes public and some returning 401. Alongside it, Boston University operates a Shibboleth SAML 2.0 identity provider at shib.bu.edu whose entity metadata is public, registered by InCommon and exported to eduGAIN with the REFEDS Research & Scholarship and SIRTFI entity categories. Everything else that looks like a Boston University API is a vendor's contract running under BU's name: OpenBU is a DSpace 7.6 instance operated by Atmire (open.bu.edu CNAMEs to boston-prod.cname.atmire.com and its OAI-PMH Identify returns the vendor's admin email), the library discovery layer is Ex Libris Primo, and the LMS is Blackboard Learn. Those are recorded here as tenant relationships, not as Boston University engineering. There is no central developer portal, no API key programme, no published API changelog, and the internal WEB APIs portal at webapi.bu.edu is NXDOMAIN.

**Areas:** University · Higher Education · Education · United States · Massachusetts · Private Research University · Research · Research Data · Library · Identity Federation · Content Management · Open Access

## Boston University on APIs.io

Everything profiled for Boston University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/boston/](https://apis.io/providers/boston/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Boston University Shibboleth Identity Provider](https://apis.io/apis/boston/shibboleth-identity-federation/) — Boston University's SAML 2.0 identity provider, publishing machine-readable entity metadata at its own host. The EntityDescriptor carries entityID…
- [OpenBU Repository — OAI-PMH and DSpace REST (Atmire-operated)](https://apis.io/apis/boston/openbu-oai/) — OpenBU is Boston University Libraries' open-access institutional repository. The content, the collections and the 2144 Handle prefix are Boston…
- [BU Libraries Discovery (Ex Libris Primo)](https://apis.io/apis/boston/primo-discovery/) — Boston University Libraries' discovery layer runs on Ex Libris Primo under Boston University's tenant view 01BOSU_INST:BULS. The catalogue data is the…
- [Blackboard Learn REST API (BU tenant)](https://apis.io/apis/boston/blackboard-learn/) — Boston University's learning management system is Blackboard Learn, running on the vendor's infrastructure behind a bu.edu hostname. The Learn public REST…
- [AI API Access (Azure OpenAI / Amazon Bedrock)](https://apis.io/apis/boston/ai-api-access/) — Boston University IS&T brokers Large Language Model API keys to affiliated faculty, researchers, staff and departments, reselling access to Microsoft Azure…
- [Boston University Website (WordPress REST)](https://apis.io/apis/boston/bu-edu-website-wordpress-rest/) — The public WordPress REST API (wp-json) of the Boston University website at www.bu.edu: the route index of the site's content management system, catalogued…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (1)

The data models the API reads and writes.

- [Boston University WordPress REST API schemas](https://apis.io/schemas/boston/boston-wordpress-schemas/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Boston Context](https://apis.io/jsonld/boston/boston-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Boston Authentication](https://apis.io/security/boston/boston-authentication/)
- [Boston Domain Security](https://apis.io/security/boston/boston-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Boston Plans Pricing](https://apis.io/plans/boston/boston-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Boston Rate Limits](https://apis.io/rate-limits/boston/boston-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Boston Finops](https://apis.io/finops/boston/boston-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.bu.edu/)
- [Documentation](https://developer.bu.edu/)
- [Support](https://www.bu.edu/tech/support/)
- [Blog](https://www.bu.edu/today/)
- [Terms of service](https://www.bu.edu/policies/conditions-of-use-policy-computing-ethics/)
- [Privacy policy](https://www.bu.edu/policies/digital-privacy-statement/)
- [GitHub](https://github.com/bu-ist)

## API Evangelist rating

**Kin Score 21.1** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 48.2 |
| Contract quality | 14.3 |
| Contract governance | 3.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 28.6 |
| Access clarity | 26.3 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/boston/](https://apis.io/providers/boston/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Boston University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/boston/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
