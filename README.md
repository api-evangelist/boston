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

Boston University is a private research university in Boston, Massachusetts (chartered 1869). This repository catalogs its public developer/API footprint as an [APIs.json](https://apisjson.org) profile, profiled under the API Evangelist **university pipeline**, whose first question is not "is there a specification?" but **who operates the thing the specification describes**.

A university is a federation of buyers rather than an API producer, and Boston University reads exactly that way. Two surfaces are genuinely institution-operated and institution-authored; four more run under bu.edu hostnames but belong to vendors and are recorded here as **tenant relationships** rather than credited to the institution.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/boston/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=boston-api-evangelist&utm_content=repo

## Type

- University / Private Research University / Index / Consumer / 3rd-Party

## Tags

University, Higher Education, Education, United States, Massachusetts, Private Research University, Research, Research Data, Library, Identity Federation, Content Management, Open Access

## APIs

### Institution-operated

- **Boston University WordPress REST API** — `x-operator: institution`. The discovery document at `https://www.bu.edu/wp-json/` advertises 237 routes across 15 namespaces. Nine of those namespaces (31 routes) are BU IS&T's own open-source WordPress plugins — `bu-alert`, `bu-access-control`, `bu-blocks`, `bu-cmb2-customizations`, `bu-navigation`, `bu-prepress`, `bu-site-manager`, `bu-slideshow`, `bu-tts` — published at [github.com/bu-ist](https://github.com/bu-ist) and documented at [developer.bu.edu](https://developer.bu.edu/). Some routes answer anonymous callers; privileged routes return `401 rest_forbidden`. Base URL: `https://www.bu.edu/wp-json`
- **Boston University Shibboleth Identity Provider** — `x-operator: institution`. Public SAML 2.0 entity metadata at `https://shib.bu.edu/idp/shibboleth`, entityID `https://shib.bu.edu/idp/shibboleth`, scopes `bu.edu` and `alum.bu.edu`. Registered by InCommon, exported to eduGAIN, SWAMID and the UK Access Management Federation, asserting REFEDS Research & Scholarship and SIRTFI. Institution-operated by definition, and the cleanest institution-authored contract in this profile.

### Tenant relationships (real institutional facts, vendor engineering)

- **OpenBU Repository — OAI-PMH and DSpace REST** — `x-operator: tenant` (Atmire). BU Libraries' institutional repository. The content, collections and `2144` Handle prefix are Boston University's; the deployment is Atmire's — `open.bu.edu` CNAMEs to `boston-prod.cname.atmire.com`, OAI-PMH `Identify` returns `adminEmail atmirenv@gmail.com`, and the DSpace 7.6 REST root advertises `atmire-versions` endpoints.
- **BU Libraries Discovery (Ex Libris Primo)** — `x-operator: tenant`. `bu.primo.exlibrisgroup.com`, view `01BOSU_INST:BULS`.
- **Blackboard Learn REST API (BU tenant)** — `x-operator: tenant`. `learn.bu.edu` CNAMEs to `bu.blackboard.com`; the public Learn REST API reports version `4000.21.0`.
- **AI API Access (Azure OpenAI / Amazon Bedrock)** — `x-operator: tenant`. IS&T brokers LLM API keys to affiliated staff behind an approval form. The APIs are Microsoft's and Amazon's; what BU operates is the key-issuing process.

No vendor specification is saved under this slug.

## Artifacts

- OpenAPI (derived from the live discovery document, not published by BU): [openapi/boston-wordpress-api-openapi.yml](openapi/boston-wordpress-api-openapi.yml) — pristine copy in [openapi/_original/](openapi/_original/)
- JSON Schema: [json-schema/boston-wordpress-schemas.json](json-schema/boston-wordpress-schemas.json)
- Examples (verbatim captures): [examples/boston-wordpress-examples.yml](examples/boston-wordpress-examples.yml)
- Authentication: [authentication/boston-authentication.yml](authentication/boston-authentication.yml)
- Errors: [errors/boston-errors.yml](errors/boston-errors.yml)
- Conformance: [conformance/boston-conformance.yml](conformance/boston-conformance.yml) — plus BU's own SAML metadata, saved unmodified at [conformance/boston-shibboleth-idp-metadata.xml](conformance/boston-shibboleth-idp-metadata.xml)
- Lifecycle: [lifecycle/boston-lifecycle.yml](lifecycle/boston-lifecycle.yml)
- Vocabulary: [vocabulary/boston-vocabulary.yml](vocabulary/boston-vocabulary.yml)
- JSON-LD: [json-ld/boston-context.jsonld](json-ld/boston-context.jsonld)
- Plans & Pricing: [plans/boston-plans-pricing.yml](plans/boston-plans-pricing.yml)
- Rate Limits: [rate-limits/boston-rate-limits.yml](rate-limits/boston-rate-limits.yml)
- FinOps: [finops/boston-finops.yml](finops/boston-finops.yml)
- Domain Security: [security/boston-domain-security.yml](security/boston-domain-security.yml)
- Review: [review.yml](review.yml)

## Conformance (Kin Score `education` regime)

| Standard | Status | Operator | Evidence |
|---|---|---|---|
| `saml` | conformant | institution | `https://shib.bu.edu/idp/shibboleth` — SAML 2.0 `EntityDescriptor` |
| `shibboleth` | conformant | institution | Shibboleth scopes `bu.edu`, `alum.bu.edu`; InCommon-registered, in eduGAIN |
| `oai-pmh` | conformant | tenant (Atmire) | `https://open.bu.edu/server/oai/request?verb=Identify`, 8 metadata prefixes, 100 sets |
| `lti` | not assessed | tenant | Blackboard Learn is LTI-certified as a product; no BU-specific declaration found |
| `orcid`, `datacite`, `crossref`, `scim`, `oneroster`, `ed-fi`, `caliper`, `qti` | not found | — | Looked for; recorded as absent rather than omitted |

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-30

## Common Properties

- Website: https://www.bu.edu/
- Documentation: https://developer.bu.edu/
- GitHub Organization: https://github.com/bu-ist (also https://github.com/bu-rcs)
- Identity Federation: https://shib.bu.edu/idp/shibboleth
- Research Repository: https://open.bu.edu/
- Library Catalog: https://bu.primo.exlibrisgroup.com/discovery/search?vid=01BOSU_INST:BULS
- Research Computing: https://www.bu.edu/tech/support/research/
- AI Policy: https://www.bu.edu/aida/ai-education/ai-at-work/generative-ai-guidelines-for-bu-faculty-staff/
- AI Tooling: https://www.bu.edu/aida/
- Support: https://www.bu.edu/tech/support/
- Terms of Service: https://www.bu.edu/policies/conditions-of-use-policy-computing-ethics/
- Privacy Policy: https://www.bu.edu/policies/digital-privacy-statement/
- Blog: https://www.bu.edu/today/ (RSS: https://www.bu.edu/today/feed/)
- LinkedIn: https://www.linkedin.com/school/boston-university/

## Notes

All entries reflect URLs probed on 2026-08-30 with no credentials of any kind; no endpoints were fabricated. Surfaces hunted and **not found**: a course catalog or registrar API, an open data portal, dining, transit, a research-computing API, `llms.txt`, `apis.json`, `/.well-known/security.txt`, and any developer portal or API key programme — `www.bu.edu` returns a real 404 for each, not a soft 404. The internal WEB APIs portal at `webapi.bu.edu` is NXDOMAIN. `bus.bu.edu` is a student-built (BostonHacks) shuttle tracker served from GitHub Pages on a delegated `bu.edu` subdomain, with no API of its own, and is not credited to the institution. `profiles.bu.edu` is a Profiles RNS deployment on Boston University's own network, but four candidate API paths all returned 404.

The single OpenAPI here was **derived** by transcribing the live WordPress discovery document and is marked as such throughout. Response schemas are left unspecified rather than invented, because Boston University publishes none. It is deliberately kept as **one document with one `apis[]` entry** rather than split per tag: ten per-tag files would read as ten times the footprint for one contract.

## Maintainers

- Kin Lane — kin@apievangelist.com
