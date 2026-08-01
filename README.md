# Boxabl

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
