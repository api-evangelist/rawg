# RAWG (rawg)

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

RAWG is the largest video game database and game discovery service, providing access to more than 350,000 games across 50+ platforms with rich metadata including tags, genres, developers, publishers, creators, release dates, Metacritic ratings, store links, ESRB ratings, average playtime, achievements, screenshots, trailers, and social media data. RAWG offers a free REST API for personal and small commercial use with API key authentication, enabling developers to search and filter games by platform, genre, developer, publisher, tag, release date, and rating. The API also provides endpoints for exploring game series, DLCs, development team members, and visually similar games (enterprise tier). RAWG is used by developers building game discovery apps, recommendation engines, gaming dashboards, and data warehouses.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Database
- Entertainment
- Game Discovery
- Games
- Gaming
- Metadata
- Video Games

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-19

## APIs

### RAWG Video Games Database API

The RAWG Video Games Database API provides programmatic access to a catalog of more than 350,000 games across 50+ platforms, including creator roles, individual creators, game developers, game publishers, genres, tags, storefronts, platforms, and detailed game metadata. The API supports pagination, search, and multi-dimensional filtering across dates, platforms, genres, tags, Metacritic scores, and more. All requests require an API key passed as a query parameter.

- **Human URL:** [https://rawg.io/apidocs](https://rawg.io/apidocs)
- **Base URL:** `https://api.rawg.io/api`

#### Tags

- Database
- Entertainment
- Game Discovery
- Games
- Gaming
- Metadata
- Video Games

#### Properties

- [Documentation](https://rawg.io/apidocs)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/openapi/rawg-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Rules](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/rules/rawg-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/json-schema/rawg-game-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/json-structure/rawg-game-structure.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/json-ld/rawg-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/vocabulary/rawg-vocabulary.yml)
- [Postman Collection](collections/rawg.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rawg.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/rawg)
- [Website](https://rawg.io)
- [Documentation](https://rawg.io/apidocs)
- [Sign Up](https://rawg.io/login?forward=developer)
- [Terms of Service](https://rawg.io/terms)
- [Blog](https://rawg.io/blog)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
