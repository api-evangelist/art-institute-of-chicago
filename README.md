# Art Institute of Chicago

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

The Art Institute of Chicago publishes an open, REST + Elasticsearch-style Public API for ~120,000 artworks plus agents (artists/makers), places, galleries, exhibitions, tours, mobile sounds, museum-shop products, publications, sections, sites, educator resources, digital and printed publications, and static archive images. Most data is CC0 1.0; descriptions and place data are CC-BY 4.0. No API key required; anonymous limit is 60 requests/minute per IP. Clients should send an AIC-User-Agent header for courtesy tracking. The canonical aggregator (Laravel) is open source on GitHub, and nightly bulk data dumps are published in a sibling repo.

**Areas:** Museums · Open Data · Cultural Heritage · IIIF · Public APIs · Open Source · Art

## Art Institute of Chicago on APIs.io

Everything profiled for Art Institute of Chicago is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/art-institute-of-chicago/](https://apis.io/providers/art-institute-of-chicago/)** — or go straight to one of the APIs or properties below.

### APIs (39)

- [IIIF Image API](https://apis.io/apis/art-institute-of-chicago/iiif-image-api/) — IIIF Image API 2.0-compliant service for delivering image binaries for artworks. Combine artwork.image_id with config.iiif_url returned by the Public API.
- [Bulk Data Dumps](https://apis.io/apis/art-institute-of-chicago/bulk-data-dumps/) — Nightly data dumps of the collection and related resources, published as JSON in a public GitHub repository. Recommended for bulk consumers instead of…
- [Art Institute of Chicago Agent Roles API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-agent-roles-api/) — Roles agents can play in relation to an artwork.
- [Art Institute of Chicago Agent Types API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-agent-types-api/) — Classifications of agents (Individual, Corporate, etc.).
- [Art Institute of Chicago Agents API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-agents-api/) — People and organizations (artists, makers, donors) associated with artworks.
- [Art Institute of Chicago Articles API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-articles-api/) — Magazine-style articles published by the museum.
- [Art Institute of Chicago Artists API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-artists-api/) — Convenience alias for agents flagged as artists.
- [Art Institute of Chicago Artwork Date Qualifiers API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-artwork-date-qualifiers-api/) — Date qualifier terms used on artworks.
- [Art Institute of Chicago Artwork Place Qualifiers API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-artwork-place-qualifiers-api/) — Place qualifier terms used on artworks.
- [Art Institute of Chicago Artwork Types API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-artwork-types-api/) — Classification of artwork types (Painting, Sculpture, etc.).
- [Art Institute of Chicago Artworks API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-artworks-api/) — Artworks from the Art Institute of Chicago collection (~120,000 records).
- [Art Institute of Chicago Category Terms API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-category-terms-api/) — Subject, department and style category terms.
- [Art Institute of Chicago Digital Publication Articles API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-digital-publication-articles-api/) — Articles inside digital publications.
- [Art Institute of Chicago Digital Publications API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-digital-publications-api/) — Online scholarly publications and catalogues.
- [Art Institute of Chicago Educator Resources API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-educator-resources-api/) — Lesson plans and resources for educators.
- [Art Institute of Chicago Event Occurrences API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-event-occurrences-api/) — Scheduled occurrences of an event.
- [Art Institute of Chicago Event Programs API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-event-programs-api/) — Recurring program series the events belong to.
- [Art Institute of Chicago Events API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-events-api/) — Public events at the museum.
- [Art Institute of Chicago Exhibitions API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-exhibitions-api/) — Past, current and upcoming exhibitions.
- [Art Institute of Chicago Galleries API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-galleries-api/) — Galleries inside the Art Institute of Chicago museum.
- [Art Institute of Chicago Generic Pages API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-generic-pages-api/) — Generic landing-style pages.
- [Art Institute of Chicago Highlights API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-highlights-api/) — Curated highlight items from the collection.
- [Art Institute of Chicago Hours API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-hours-api/) — Museum opening hours.
- [Art Institute of Chicago Images API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-images-api/) — Image assets (delivered via IIIF for binary data).
- [Art Institute of Chicago Landing Pages API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-landing-pages-api/) — Top-level landing pages of artic.edu.
- [Art Institute of Chicago Mobile Sounds API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-mobile-sounds-api/) — Audio tour stops and mobile-app sound content.
- [Art Institute of Chicago Places API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-places-api/) — Geographic places linked to artworks (uses Getty Thesaurus of Geographic Names).
- [Art Institute of Chicago Press Releases API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-press-releases-api/) — Official press releases from the museum.
- [Art Institute of Chicago Printed Publications API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-printed-publications-api/) — Print catalogues and books.
- [Art Institute of Chicago Products API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-products-api/) — Items for sale in the museum shop.
- [Art Institute of Chicago Publications API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-publications-api/) — All museum publications (combined index).
- [Art Institute of Chicago Search API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-search-api/) — Cross-resource Elasticsearch-style search.
- [Art Institute of Chicago Sections API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-sections-api/) — Sections of online publications and catalogues.
- [Art Institute of Chicago Sites API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-sites-api/) — Microsites and online sites published by the museum.
- [Art Institute of Chicago Sounds API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-sounds-api/) — Sound assets and metadata.
- [Art Institute of Chicago Static Pages API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-static-pages-api/) — Static content pages of artic.edu.
- [Art Institute of Chicago Texts API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-texts-api/) — Long-form text content.
- [Art Institute of Chicago Tours API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-tours-api/) — Curated multi-stop museum tours.
- [Art Institute of Chicago Videos API](https://apis.io/apis/art-institute-of-chicago/art-institute-of-chicago-videos-api/) — Video assets and metadata.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Art Institute Of Chicago Agentic Access](https://apis.io/agentic-access/art-institute-of-chicago/art-institute-of-chicago-agentic-access/)

#### JSON Schema (7)

The data models the API reads and writes.

- [Agent](https://apis.io/schemas/art-institute-of-chicago/art-institute-of-chicago-agent/)
- [Artwork](https://apis.io/schemas/art-institute-of-chicago/art-institute-of-chicago-artwork/)
- [Exhibition](https://apis.io/schemas/art-institute-of-chicago/art-institute-of-chicago-exhibition/)
- [Gallery](https://apis.io/schemas/art-institute-of-chicago/art-institute-of-chicago-gallery/)
- [Place](https://apis.io/schemas/art-institute-of-chicago/art-institute-of-chicago-place/)
- [Product](https://apis.io/schemas/art-institute-of-chicago/art-institute-of-chicago-product/)
- [Tour](https://apis.io/schemas/art-institute-of-chicago/art-institute-of-chicago-tour/)

#### JSON Structure (7)

Data models expressed in JSON Structure.

- [Art Institute Of Chicago Agent Structure](https://apis.io/json-structure/art-institute-of-chicago/art-institute-of-chicago-agent-structure/)
- [Art Institute Of Chicago Artwork Structure](https://apis.io/json-structure/art-institute-of-chicago/art-institute-of-chicago-artwork-structure/)
- [Art Institute Of Chicago Exhibition Structure](https://apis.io/json-structure/art-institute-of-chicago/art-institute-of-chicago-exhibition-structure/)
- [Art Institute Of Chicago Gallery Structure](https://apis.io/json-structure/art-institute-of-chicago/art-institute-of-chicago-gallery-structure/)
- [Art Institute Of Chicago Place Structure](https://apis.io/json-structure/art-institute-of-chicago/art-institute-of-chicago-place-structure/)
- [Art Institute Of Chicago Product Structure](https://apis.io/json-structure/art-institute-of-chicago/art-institute-of-chicago-product-structure/)
- [Art Institute Of Chicago Tour Structure](https://apis.io/json-structure/art-institute-of-chicago/art-institute-of-chicago-tour-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Art Institute Of Chicago Context](https://apis.io/jsonld/art-institute-of-chicago/art-institute-of-chicago-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Art Institute of Chicago Vocabulary](https://apis.io/vocabularies/art-institute-of-chicago/art-institute-of-chicago-vocabulary/)

#### Examples (8)

Example requests and responses.

- [Art Institute Of Chicago Agents List Example](https://apis.io/examples/art-institute-of-chicago/art-institute-of-chicago-agents-list-example/)
- [Art Institute Of Chicago Artworks List Example](https://apis.io/examples/art-institute-of-chicago/art-institute-of-chicago-artworks-list-example/)
- [Art Institute Of Chicago Exhibitions List Example](https://apis.io/examples/art-institute-of-chicago/art-institute-of-chicago-exhibitions-list-example/)
- [Art Institute Of Chicago Exhibitions Search Example](https://apis.io/examples/art-institute-of-chicago/art-institute-of-chicago-exhibitions-search-example/)
- [Art Institute Of Chicago Galleries List Example](https://apis.io/examples/art-institute-of-chicago/art-institute-of-chicago-galleries-list-example/)
- [Art Institute Of Chicago Places List Example](https://apis.io/examples/art-institute-of-chicago/art-institute-of-chicago-places-list-example/)
- [Art Institute Of Chicago Products List Example](https://apis.io/examples/art-institute-of-chicago/art-institute-of-chicago-products-list-example/)
- [Art Institute Of Chicago Tours List Example](https://apis.io/examples/art-institute-of-chicago/art-institute-of-chicago-tours-list-example/)

#### Collections (38)

Postman and Open Collection request collections.

- [Art Institute of Chicago Public API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago/)
- [Art Institute of Chicago Public Agent Roles API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-agent-roles-api/)
- [Art Institute of Chicago Public Agent Roles Agent Types API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-agent-types-api/)
- [Art Institute of Chicago Public Agent Roles Agents API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-agents-api/)
- [Art Institute of Chicago Public Agent Roles Articles API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-articles-api/)
- [Art Institute of Chicago Public Agent Roles Artists API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-artists-api/)
- [Art Institute of Chicago Public Agent Roles Artwork Date Qualifiers API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-artwork-date-qualifiers-api/)
- [Art Institute of Chicago Public Agent Roles Artwork Place Qualifiers API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-artwork-place-qualifiers-api/)
- [Art Institute of Chicago Public Agent Roles Artwork Types API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-artwork-types-api/)
- [Art Institute of Chicago Public Agent Roles Artworks API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-artworks-api/)
- [Art Institute of Chicago Public Agent Roles Category Terms API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-category-terms-api/)
- [Art Institute of Chicago Public Agent Roles Digital Publication Articles API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-digital-publication-articles-api/)
- [Art Institute of Chicago Public Agent Roles Digital Publications API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-digital-publications-api/)
- [Art Institute of Chicago Public Agent Roles Educator Resources API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-educator-resources-api/)
- [Art Institute of Chicago Public Agent Roles Event Occurrences API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-event-occurrences-api/)
- [Art Institute of Chicago Public Agent Roles Event Programs API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-event-programs-api/)
- [Art Institute of Chicago Public Agent Roles Events API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-events-api/)
- [Art Institute of Chicago Public Agent Roles Exhibitions API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-exhibitions-api/)
- [Art Institute of Chicago Public Agent Roles Galleries API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-galleries-api/)
- [Art Institute of Chicago Public Agent Roles Generic Pages API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-generic-pages-api/)
- [Art Institute of Chicago Public Agent Roles Highlights API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-highlights-api/)
- [Art Institute of Chicago Public Agent Roles Hours API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-hours-api/)
- [Art Institute of Chicago Public Agent Roles Images API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-images-api/)
- [Art Institute of Chicago Public Agent Roles Landing Pages API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-landing-pages-api/)
- [Art Institute of Chicago Public Agent Roles Mobile Sounds API](https://apis.io/collections/art-institute-of-chicago/open-art-institute-of-chicago-mobile-sounds-api/)
- …and 13 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Art Institute of Chicago — jsonschema rules](https://apis.io/rules/art-institute-of-chicago/art-institute-of-chicago-jsonschema-spectral-rules/)
- [Art Institute of Chicago API Rules](https://apis.io/rules/art-institute-of-chicago/art-institute-of-chicago-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Art Institute Of Chicago Domain Security](https://apis.io/security/art-institute-of-chicago/art-institute-of-chicago-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Art Institute Of Chicago Plans Pricing](https://apis.io/plans/art-institute-of-chicago/art-institute-of-chicago-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Art Institute Of Chicago Rate Limits](https://apis.io/rate-limits/art-institute-of-chicago/art-institute-of-chicago-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Blog](https://www.artic.edu/blog)

## API Evangelist rating

**Unrated** — no public website could be reached for this company, so there was almost nothing to measure and nothing a reader could check.

This is not a score of zero. No rating is published for this company. If that is wrong because something public exists that we missed, say so on this repository or email [info@apievangelist.com](mailto:info@apievangelist.com) and it will be re-run — free, and no justification needed.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Art Institute of Chicago: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/art-institute-of-chicago/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
