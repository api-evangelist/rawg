# RAWG

RAWG is the largest video game database and game discovery service, providing access to more than 350,000 games across 50+ platforms with rich metadata including tags, genres, developers, publishers, creators, release dates, Metacritic ratings, store links, ESRB ratings, playtime, achievements, screenshots, trailers, and social data. RAWG offers a free REST API for personal and small commercial use with API key authentication.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Database, Entertainment, Game Discovery, Games, Gaming, Metadata, Video Games

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-02

## APIs

### RAWG Video Games Database API

The RAWG Video Games Database API provides programmatic access to a catalog of more than 350,000 games across 50+ platforms, including creator roles, individual creators, game developers, game publishers, genres, tags, storefronts, platforms, and detailed game metadata. The API supports pagination, search, and multi-dimensional filtering. All requests require an API key passed as a query parameter.

**Human URL:** [https://rawg.io/apidocs](https://rawg.io/apidocs)

**Base URL:** https://api.rawg.io/api

#### Tags

Database, Entertainment, Game Discovery, Games, Gaming, Metadata, Video Games

#### Properties

- [Documentation](https://rawg.io/apidocs)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/openapi/rawg-openapi.yml)
- [Rules](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/rules/rawg-rules.yml)
- [JSONSchema](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/json-schema/rawg-game-schema.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/json-structure/rawg-game-structure.json)
- [JSONLd](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/json-ld/rawg-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/vocabulary/rawg-vocabulary.yml)

#### Endpoints

| Method | Path | Summary |
|---|---|---|
| GET | /creator-roles | List Creator Roles |
| GET | /creators | List Creators |
| GET | /creators/{id} | Get Creator Details |
| GET | /developers | List Developers |
| GET | /developers/{id} | Get Developer Details |
| GET | /games | List Games |
| GET | /games/{id} | Get Game Details |
| GET | /games/{game_pk}/additions | List Game Additions |
| GET | /games/{game_pk}/development-team | List Game Development Team |
| GET | /games/{game_pk}/game-series | List Game Series |
| GET | /games/{game_pk}/parent-games | List Game Parent Games |
| GET | /games/{game_pk}/screenshots | List Game Screenshots |
| GET | /games/{game_pk}/stores | List Game Store Links |
| GET | /games/{id}/achievements | List Game Achievements |
| GET | /games/{id}/movies | List Game Trailers |
| GET | /games/{id}/reddit | List Game Reddit Posts |
| GET | /games/{id}/suggested | List Suggested Games |
| GET | /genres | List Genres |
| GET | /genres/{id} | Get Genre Details |
| GET | /platforms | List Platforms |
| GET | /platforms/lists/parents | List Parent Platforms |
| GET | /platforms/{id} | Get Platform Details |
| GET | /publishers | List Publishers |
| GET | /publishers/{id} | Get Publisher Details |
| GET | /stores | List Stores |
| GET | /stores/{id} | Get Store Details |
| GET | /tags | List Tags |
| GET | /tags/{id} | Get Tag Details |

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/rawg-video-games-database.yaml](capabilities/shared/rawg-video-games-database.yaml) | Full RAWG API consumed definition with all resources and operations |

### Workflow Capabilities

| File | Description |
|---|---|
| [capabilities/game-discovery.yaml](capabilities/game-discovery.yaml) | Unified game discovery workflow — search, filter, and retrieve game metadata with REST and MCP adapters (21 tools) |

## Artifacts

| Type | File |
|---|---|
| OpenAPI | [openapi/rawg-openapi.yml](openapi/rawg-openapi.yml) |
| Spectral Rules | [rules/rawg-rules.yml](rules/rawg-rules.yml) |
| JSON Schema | [json-schema/rawg-game-schema.json](json-schema/rawg-game-schema.json) |
| JSON Structure | [json-structure/rawg-game-structure.json](json-structure/rawg-game-structure.json) |
| JSON-LD Context | [json-ld/rawg-context.jsonld](json-ld/rawg-context.jsonld) |
| Vocabulary | [vocabulary/rawg-vocabulary.yml](vocabulary/rawg-vocabulary.yml) |
| Examples | [examples/](examples/) |

## Common Properties

- [Website](https://rawg.io)
- [Documentation](https://rawg.io/apidocs)
- [SignUp](https://rawg.io/login?forward=developer)
- [TermsOfService](https://rawg.io/terms)
- [Blog](https://rawg.io/blog)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
