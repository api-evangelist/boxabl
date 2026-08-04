# Boxabl

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

BOXABL Inc. is a Las Vegas, Nevada manufacturer of factory-built, foldable homes, founded in 2017 and trading on Nasdaq under the ticker BXBL. Homes are assembled on a production line in a climate-controlled factory, folded to 8.5 x 20 feet for shipment, and unfolded on site in about two hours. The Casita is the current production model (studio, one-bedroom, two-bedroom; unit-only or turnkey), alongside the Baby Box travel trailer and a multi-unit Developer Series catalog.

- https://www.boxabl.com/
- https://forgeglobal.com/boxabl_stock/

## API surface

**BOXABL publishes no public API.** Contract discovery was run against `boxabl.com`, `www.boxabl.com`, `api.boxabl.com` (NXDOMAIN) and `gcdn.boxabl.com`: no OpenAPI/Swagger at any host root, no GraphQL endpoint, no MCP server, no A2A agent card at either the canonical or legacy well-known path, no AsyncAPI or webhook surface, and no first-party SDK on any package registry. The `/developers` page is a housing catalog for real-estate developers, not a developer portal.

## What it does publish

- **`llms/boxabl-llms.txt`** — a real, well-formed `llms.txt` served at `https://www.boxabl.com/llms.txt`, saved verbatim. Products with price ranges and dimensions, shipping states, company facts, key pages, and an explicit answer-engine usage clause. Paired with a robots.txt that names GPTBot, ClaudeBot, PerplexityBot, Google-Extended, Applebot-Extended and CCBot with `Allow: /`.
- **`well-known/boxabl-security.txt`** — an unexpired RFC 9116 `security.txt`.
- **`security/boxabl-vulnerability-disclosure.yml`** — a genuine responsible-disclosure / bug bounty program with defined scope, rules of engagement, safe harbour, `bugs@boxabl.com` submission channel and CVSS-linked discretionary compensation.
- **`security/boxabl-domain-security.yml`** — strong domain posture: TLS 1.3, HSTS `max-age=63072000`, DNSSEC enabled, CAA records set, SPF present, DMARC `p=reject`.
