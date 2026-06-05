# Art Institute of Chicago (art-institute-of-chicago)

The Art Institute of Chicago publishes an open, REST + Elasticsearch-style Public API for ~120,000 artworks plus agents (artists/makers), places, galleries, exhibitions, tours, mobile sounds, museum-shop products, publications, sections, sites, educator resources, digital and printed publications, and static archive images. Most data is CC0 1.0; descriptions and place data are CC-BY 4.0. No API key required; anonymous limit is 60 requests/minute per IP. Clients should send an AIC-User-Agent header for courtesy tracking. The canonical aggregator (Laravel) is open source on GitHub, and nightly bulk data dumps are published in a sibling repo.

**APIs.json:** [https://api.artic.edu/docs/](https://api.artic.edu/docs/)

## Tags

- Art And Design
- Museum
- Open Data
- Cultural Heritage
- IIIF
- Public APIs
- Open Source

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### Art Institute of Chicago Public API

Open REST and search API surfacing the museum's collection, agents, exhibitions, tours, publications, products and operational data (galleries, hours, sites). Backed by Elasticsearch; data refreshed nightly. Read-only.

- **Human URL:** [https://api.artic.edu/docs/](https://api.artic.edu/docs/)
- **Base URL:** `https://api.artic.edu/api/v1`

#### Tags

- Art And Design
- Museum
- Open Data

#### Properties

- [Documentation](https://api.artic.edu/docs/)
- [OpenAPI](openapi/art-institute-of-chicago-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/art-institute-of-chicago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/art-institute-of-chicago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://api.artic.edu/api/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://api.artic.edu/docs/)
- [Rate Limits](rate-limits/art-institute-of-chicago-rate-limits.yml)
- [License](https://creativecommons.org/publicdomain/zero/1.0/)
- [Example](examples/art-institute-of-chicago-artworks-list-example.json)
- [Example](examples/art-institute-of-chicago-agents-list-example.json)
- [Example](examples/art-institute-of-chicago-exhibitions-list-example.json)
- [Example](examples/art-institute-of-chicago-galleries-list-example.json)
- [Example](examples/art-institute-of-chicago-places-list-example.json)
- [Example](examples/art-institute-of-chicago-products-list-example.json)
- [Example](examples/art-institute-of-chicago-tours-list-example.json)
- [Example](examples/art-institute-of-chicago-exhibitions-search-example.json)
- [JSON Schema](json-schema/art-institute-of-chicago-artwork-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/art-institute-of-chicago-agent-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/art-institute-of-chicago-place-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/art-institute-of-chicago-gallery-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/art-institute-of-chicago-exhibition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/art-institute-of-chicago-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/art-institute-of-chicago-tour-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/art-institute-of-chicago-artwork-structure.json)
- [JSON Structure](json-structure/art-institute-of-chicago-agent-structure.json)
- [JSON Structure](json-structure/art-institute-of-chicago-place-structure.json)
- [JSON Structure](json-structure/art-institute-of-chicago-gallery-structure.json)
- [JSON Structure](json-structure/art-institute-of-chicago-exhibition-structure.json)
- [JSON Structure](json-structure/art-institute-of-chicago-product-structure.json)
- [JSON Structure](json-structure/art-institute-of-chicago-tour-structure.json)
- [J S O N- L D](json-ld/art-institute-of-chicago-context.jsonld)

### IIIF Image API

IIIF Image API 2.0-compliant service for delivering image binaries for artworks. Combine artwork.image_id with config.iiif_url returned by the Public API.

- **Human URL:** [https://api.artic.edu/docs/#iiif-image-api](https://api.artic.edu/docs/#iiif-image-api)
- **Base URL:** `https://www.artic.edu/iiif/2`

#### Tags

- IIIF
- Images

#### Properties

- [Documentation](https://api.artic.edu/docs/#iiif-image-api)
- [Specification](https://iiif.io/api/image/2.0/)
- [Postman Collection](collections/art-institute-of-chicago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/art-institute-of-chicago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bulk Data Dumps

Nightly data dumps of the collection and related resources, published as JSON in a public GitHub repository. Recommended for bulk consumers instead of scraping the API.

- **Human URL:** [https://github.com/art-institute-of-chicago/api-data](https://github.com/art-institute-of-chicago/api-data)
- **Base URL:** `https://github.com/art-institute-of-chicago/api-data`

#### Tags

- Bulk Data
- Open Data

#### Properties

- [GitHub Repository](https://github.com/art-institute-of-chicago/api-data)
- [Postman Collection](collections/art-institute-of-chicago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/art-institute-of-chicago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.artic.edu/)
- [Documentation](https://api.artic.edu/docs/)
- [Portal](https://api.artic.edu/docs/)
- [Terms of Service](https://www.artic.edu/terms/terms-and-conditions)
- [Privacy Policy](https://www.artic.edu/privacy)
- [Support](mailto:engineering@artic.edu)
- [GitHub Organization](https://github.com/art-institute-of-chicago)
- [GitHub Repository](https://github.com/art-institute-of-chicago/data-aggregator)
- [GitHub Repository](https://github.com/art-institute-of-chicago/api-data)
- [GitHub Repository](https://github.com/art-institute-of-chicago/aic-bash)
- [SDK](https://github.com/art-institute-of-chicago/aic-bash)
- [Tools](https://github.com/art-institute-of-chicago/browser-extension)
- [Tools](https://github.com/art-institute-of-chicago/aic-mobile-android)
- [Tools](https://github.com/art-institute-of-chicago/aic-mobile-ios)
- [Tools](https://github.com/art-institute-of-chicago/aic-mobile-cms)
- [Tools](https://github.com/art-institute-of-chicago/twill)
- [Tools](https://github.com/mikechao/artic-mcp)
- [Spectral Rules](rules/art-institute-of-chicago-rules.yml)
- [Vocabulary](vocabulary/art-institute-of-chicago-vocabulary.yml)
- [Plans](plans/art-institute-of-chicago-plans-pricing.yml)
- [Rate Limits](rate-limits/art-institute-of-chicago-rate-limits.yml)
- [Public APIs Listing](https://github.com/public-apis/public-apis)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
