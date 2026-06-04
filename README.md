# Boston University (boston)

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
