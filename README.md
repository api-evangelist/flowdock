# Flowdock (Discontinued)

> **Status: DISCONTINUED — August 15, 2023.**
> CA Flowdock was a team chat and shared team-inbox product. The hosted
> service and all public APIs (REST, Push, Streaming, SCIM) were shut down
> on 2023-08-15 by Broadcom. The official sunset notice directed customers
> to **Microsoft Teams** or **Slack** as successors.

This repository is an **archival API Evangelist profile** of Flowdock,
reconstructed from the public
[`flowdock/api-docs`](https://github.com/flowdock/api-docs) repository and
archived snapshots of the developer portal on the Internet Archive
(closest snapshot: 2021-12-06). No live endpoint listed here is reachable
today — everything below is captured for historical, migration, and
research use.

## Vendor history

- **~2010** — Founded as Flowdock in Helsinki / Tampere, Finland, as a
  spin-off from Nodeta Oy.
- **2013** — Acquired by **CA Technologies**; rebranded *CA Flowdock*.
- **2018** — **Broadcom** acquires CA Technologies; Flowdock falls under
  Broadcom Enterprise Software.
- **2023-08-15** — Hosted service and all public APIs discontinued;
  successor recommendation: Microsoft Teams or Slack.

## APIs profiled

| # | API | Status | Spec |
|---|-----|--------|------|
| 1 | **Flowdock REST API** — flows, messages, threads, private conversations, users, organizations, sources, invitations, files. OAuth 2.0 + Basic + personal token. | Discontinued | [`openapi/flowdock-rest-api-openapi.yml`](openapi/flowdock-rest-api-openapi.yml) |
| 2 | **Flowdock Push API** — legacy write-only token-scoped post into Team Inbox / Chat. Vendor-deprecated. | Discontinued | [`openapi/flowdock-push-api-openapi.yml`](openapi/flowdock-push-api-openapi.yml) |
| 3 | **Flowdock Streaming API** — long-lived HTTP stream over `stream.flowdock.com`, JSON or Server-Sent Events. | Discontinued | [`asyncapi/flowdock-streaming-api-asyncapi.yml`](asyncapi/flowdock-streaming-api-asyncapi.yml) |
| 4 | **Flowdock SCIM API** — partial SCIM 1.x user provisioning for Enterprise SSO tenants. | Discontinued | [`openapi/flowdock-scim-api-openapi.yml`](openapi/flowdock-scim-api-openapi.yml) |

## Artifact inventory

| Folder | Count | Notes |
|--------|-------|-------|
| `openapi/` | 3 | REST, Push, SCIM. |
| `asyncapi/` | 1 | Streaming. |
| `json-schema/` | 7 | Flow, Message, User, Organization, Source, Thread, Invitation. |
| `json-structure/` | 3 | Flow, Message, Organization. |
| `json-ld/` | 1 | `flowdock-context.jsonld`. |
| `examples/` | 9 | Flow list, message send, push (inbox + chat), private conversation, invitation, sources, streaming event, SCIM user. |
| `capabilities/` | 6 | 4 shared (REST, Push, Streaming, SCIM) + 2 workflows (`post-to-flow`, `integration-source`). |
| `rules/` | 1 | `flowdock-rules.yml` (Spectral). |
| `vocabulary/` | 1 | `flowdock-vocabulary.yml`. |

## Notable absences

- **No live developer portal** — `www.flowdock.com` and `api.flowdock.com`
  are offline. Documentation only survives via the `flowdock/api-docs`
  GitHub repo and Internet Archive snapshots.
- **No public OpenAPI spec was ever published by the vendor** — the specs
  in `openapi/` are reconstructions from the markdown documentation.
- **No public pricing, status page, RSS feed, or changelog** is reachable
  today. The historical pricing tiers and SLAs are no longer documented.
- **No published per-endpoint rate limits** other than the SCIM-auth rate
  limit hint (`429` on failed auth attempts).
- **No surviving FinOps surface** — billing was bundled with the wider
  CA / Broadcom enterprise contracts; no public cost API existed.
- All `flowdock/*` GitHub repositories (SDKs, integrations, api-docs)
  are now **archived**.

## Migration recommendations (per Broadcom's sunset notice)

- **Slack** — direct functional successor for team chat + integrations.
- **Microsoft Teams** — Microsoft 365–bundled successor with similar
  chat + threading + integration model.

## Sources

- [`flowdock/api-docs`](https://github.com/flowdock/api-docs) — original
  Markdown documentation.
- [Internet Archive snapshot of /api](https://web.archive.org/web/20211206180655/https://www.flowdock.com/api) — 2021-12-06.
- [`flowdock` GitHub org](https://github.com/flowdock) — archived SDKs and integrations.

---

Profile maintained by [API Evangelist](https://apievangelist.com).
