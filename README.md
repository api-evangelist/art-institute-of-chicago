# Art Institute of Chicago (art-institute-of-chicago)

The Art Institute of Chicago publishes an open, REST + Elasticsearch-style
Public API for ~120,000 artworks plus agents (artists/makers), places,
galleries, exhibitions, tours, mobile sounds, museum-shop products,
publications, sections, sites, educator resources, digital and printed
publications, and static archive images. Most data is CC0 1.0; descriptions and
place data are CC-BY 4.0. No API key required; anonymous limit is 60
requests/minute per IP. Clients should send an AIC-User-Agent header for
courtesy tracking.

- **Portal:** https://api.artic.edu/docs/
- **Base URL:** https://api.artic.edu/api/v1
- **OpenAPI (provider):** https://api.artic.edu/api/v1/openapi.json
- **GitHub org:** https://github.com/art-institute-of-chicago
- **Source aggregator:** https://github.com/art-institute-of-chicago/data-aggregator (Laravel)
- **Bulk data dumps:** https://github.com/art-institute-of-chicago/api-data

**APIs.yml:** [apis.yml](apis.yml)

## Type
- **x-type:** opensource
- **x-tier:** 2 (opensource with public OpenAPI and community MCP server)
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Art & Design

## APIs

### Art Institute of Chicago Public API
Open REST and search API surfacing the collection plus agents, exhibitions,
tours, publications, products and operational data. Backed by Elasticsearch;
data refreshed nightly. Read-only. 103 documented operations across 37 tag
groups.

- Documentation: https://api.artic.edu/docs/
- OpenAPI (local, cleaned): [openapi/art-institute-of-chicago-openapi.yml](openapi/art-institute-of-chicago-openapi.yml)
- OpenAPI (provider): https://api.artic.edu/api/v1/openapi.json

### IIIF Image API
IIIF Image API 2.0-compliant service for delivering image binaries. Combine
`artwork.image_id` with `config.iiif_url` from any Public API response.

- Documentation: https://api.artic.edu/docs/#iiif-image-api
- Spec: https://iiif.io/api/image/2.0/

### Bulk Data Dumps
Nightly JSON dumps of the collection and related resources. Recommended for
bulk consumers instead of scraping.

- Repo: https://github.com/art-institute-of-chicago/api-data

## Artifacts

| Type | Path | Count |
|---|---|---|
| OpenAPI | [openapi/](openapi/) | 1 |
| JSON Schema | [json-schema/](json-schema/) | 7 |
| JSON Structure | [json-structure/](json-structure/) | 7 |
| JSON-LD context | [json-ld/](json-ld/) | 1 |
| Examples | [examples/](examples/) | 8 |
| Spectral rules | [rules/](rules/) | 1 |
| Naftiko capabilities | [capabilities/](capabilities/) | 7 + 1 shared |
| Vocabulary | [vocabulary/](vocabulary/) | 1 |
| Plans | [plans/](plans/) | 1 |
| Rate limits | [rate-limits/](rate-limits/) | 1 |

## Authentication & Rate Limits

- **Auth:** None. Public API; no key required.
- **Required courtesy header:** `AIC-User-Agent: AppName (contact-email)`
- **Rate limit:** 60 requests/minute per IP (anonymous). Contact
  `engineering@artic.edu` for higher limits.
- **Bulk:** Prefer nightly dumps over scraping.

## License

- Most data: **CC0 1.0** — public domain dedication.
- Artwork descriptions: **CC-BY 4.0** — attribution required.
- Place data: **CC-BY 4.0** (includes Getty TGN data under ODC-BY).

## Tooling Ecosystem

- **Official mobile apps:** [aic-mobile-android](https://github.com/art-institute-of-chicago/aic-mobile-android), [aic-mobile-ios](https://github.com/art-institute-of-chicago/aic-mobile-ios), CMS in [aic-mobile-cms](https://github.com/art-institute-of-chicago/aic-mobile-cms)
- **CMS:** [twill](https://github.com/art-institute-of-chicago/twill) — open-source Laravel admin toolkit originally built at AIC
- **Bash SDK:** [aic-bash](https://github.com/art-institute-of-chicago/aic-bash) — ASCII-art rendering of public-domain artworks
- **Browser extension:** [browser-extension](https://github.com/art-institute-of-chicago/browser-extension) — random artwork in new tab
- **Community MCP server:** [mikechao/artic-mcp](https://github.com/mikechao/artic-mcp) — Model Context Protocol access to the collection (TypeScript, MIT)

## Tags
Art And Design, Museum, Open Data, Cultural Heritage, IIIF, Public APIs, Open Source

## Timestamps
- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## Maintainers
- **Kin Lane** — kin@apievangelist.com
