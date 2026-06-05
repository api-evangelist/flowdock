# Flowdock (Discontinued) (flowdock)

CA Flowdock was a team chat and shared team-inbox product originally
founded as Flowdock in Helsinki / Tampere, Finland (Nodeta Oy spin-off,
~2010), acquired by CA Technologies in 2013, and operated under Broadcom
after Broadcom's 2018 acquisition of CA. The hosted service and all
public APIs (REST, Push, Streaming, SCIM) were discontinued on
August 15, 2023. Broadcom's sunset notice directed customers to
Microsoft Teams or Slack as successor products. This profile is an
archival record assembled from the public api-docs repository and
archived snapshots of the developer portal.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flowdock/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flowdock/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Team Chat
- Team Inbox
- Collaboration
- Real-Time Messaging
- Integrations
- Discontinued

## Timestamps

- **Created:** 2026-05-22
- **Modified:** 2026-05-22

## APIs

### Flowdock REST API

The primary developer surface for Flowdock. Read-write JSON over HTTPS
for flows, messages, threads, private conversations, users,
organizations, sources, invitations, and files. Authenticated via
OAuth 2.0 (authorization-code), HTTP Basic with email+password, or
personal API token. Now offline.

- **Human URL:** [https://github.com/flowdock/api-docs](https://github.com/flowdock/api-docs)
- **Base URL:** `https://api.flowdock.com`

#### Tags

- Team Chat
- Team Inbox
- REST
- Discontinued

#### Properties

- [Documentation](https://github.com/flowdock/api-docs)
- [API Reference](https://web.archive.org/web/20211206180655/https://www.flowdock.com/api/rest)
- [Authentication](https://web.archive.org/web/20211206180655/https://www.flowdock.com/api/authentication)
- [OpenAPI](openapi/flowdock-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flowdock-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flowdock-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/flowdock-rules.yml)
- [JSON Schema](json-schema/flowdock-flow-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flowdock-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flowdock-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flowdock-organization-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flowdock-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flowdock-thread-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flowdock-invitation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flowdock-flow-structure.json)
- [JSON Structure](json-structure/flowdock-message-structure.json)
- [JSON Structure](json-structure/flowdock-organization-structure.json)
- [Example](examples/flowdock-list-flows-response.json)
- [Example](examples/flowdock-send-message-request.json)
- [Example](examples/flowdock-list-sources-response.json)
- [Example](examples/flowdock-private-conversation-response.json)
- [Example](examples/flowdock-invitation-response.json)

### Flowdock Push API (Deprecated)

Legacy write-only HTTP API for posting content into a Flow's Team
Inbox or Chat using a per-flow API token (no user authentication).
Deprecated by the vendor in favor of the REST Messages endpoint
well before the 2023-08-15 shutdown.

- **Human URL:** [https://github.com/flowdock/api-docs/blob/master/docs/push.md](https://github.com/flowdock/api-docs/blob/master/docs/push.md)
- **Base URL:** `https://api.flowdock.com`

#### Tags

- Push
- Webhook
- Team Inbox
- Discontinued

#### Properties

- [Documentation](https://github.com/flowdock/api-docs/blob/master/docs/push.md)
- [API Reference](https://web.archive.org/web/20211206180655/https://www.flowdock.com/api/push)
- [OpenAPI](openapi/flowdock-push-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flowdock-push-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flowdock-push-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/flowdock-team-inbox-push-request.json)
- [Example](examples/flowdock-chat-push-request.json)

### Flowdock Streaming API

Long-lived HTTP connection to stream.flowdock.com delivering real-time
flow events. Two content types: newline-delimited JSON
(`application/json`, `\r` delimited) or HTML5 Server-Sent Events
(`text/event-stream`). Now offline.

- **Human URL:** [https://github.com/flowdock/api-docs/blob/master/docs/streaming.md](https://github.com/flowdock/api-docs/blob/master/docs/streaming.md)
- **Base URL:** `https://stream.flowdock.com`

#### Tags

- Streaming
- Real-Time
- Server Sent Events
- Discontinued

#### Properties

- [Documentation](https://github.com/flowdock/api-docs/blob/master/docs/streaming.md)
- [API Reference](https://web.archive.org/web/20211206180655/https://www.flowdock.com/api/streaming)
- [AsyncAPI](asyncapi/flowdock-streaming-api-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Example](examples/flowdock-message-event-stream.json)
- [Postman Collection](collections/flowdock-push-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flowdock-push-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/flowdock-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flowdock-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/flowdock-scim-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flowdock-scim-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flowdock SCIM Provisioning API

Partial SCIM 1.x user provisioning API for CA Flowdock Enterprise
customers with Single Sign-On configured. Bearer-token authenticated.
Now offline.

- **Human URL:** [https://github.com/flowdock/api-docs/blob/master/docs/scim.md](https://github.com/flowdock/api-docs/blob/master/docs/scim.md)
- **Base URL:** `https://api.flowdock.com`

#### Tags

- SCIM
- SSO
- Provisioning
- Enterprise
- Discontinued

#### Properties

- [Documentation](https://github.com/flowdock/api-docs/blob/master/docs/scim.md)
- [OpenAPI](openapi/flowdock-scim-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flowdock-scim-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flowdock-scim-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/flowdock-scim-user-response.json)

## Common Properties

- [Portal](https://web.archive.org/web/2022/https://www.flowdock.com/)
- [Documentation](https://github.com/flowdock/api-docs)
- [Blog](https://web.archive.org/web/2022/https://blog.flowdock.com/)
- [Git Hub](https://github.com/flowdock)
- [Twitter](https://twitter.com/flowdock)
- [Facebook](https://www.facebook.com/flowdock)
- [Parent Company](https://www.broadcom.com)
- [Sunset Notice](https://www.broadcom.com)
- [Vocabulary](vocabulary/flowdock-vocabulary.yml)
- [JSON-LD](json-ld/flowdock-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [SDK](https://github.com/flowdock/flowdock-api)
- [SDK](https://github.com/flowdock/node-flowdock)
- [SDK](https://github.com/flowdock/flowdock-text)
- [SDK](https://github.com/flowdock/flowdock-text-rb)
- [SDK](https://github.com/flowdock/markdown-it-flowdock)
- [SDK](https://github.com/flowdock/omniauth-flowdock)
- [SDK](https://github.com/flowdock/hubot-flowdock)
- [Integration](https://github.com/flowdock/jenkins-flowdock-plugin)
- [Integration](https://github.com/flowdock/flowdock-jira-plugin)
- [Integration](https://github.com/flowdock/flowdock-git-hook)
- [Integration](https://github.com/flowdock/flowdock-svn-hook)
- [Integration](https://github.com/flowdock/flowdock-confluence-plugin)
- [Integration](https://github.com/flowdock/capistrano-flowdock)
- [Integration](https://github.com/flowdock/dropbox-flowdock)
- [Integration](https://github.com/flowdock/redmine_flowdock)
- [Integration](https://github.com/flowdock/oulu)
- [Integration](https://github.com/flowdock/flowdock-example-integration)
- [SDK](https://github.com/RallySoftware/clj-flowdock)
- [SDK](https://github.com/0xAX/eflowdock)
- [SDK](https://github.com/wm/go-flowdock)
- [SDK](https://github.com/njern/flowdock)
- [SDK](https://hackage.haskell.org/package/flowdock)
- [SDK](https://hackage.haskell.org/package/flowdock-api)
- [SDK](https://github.com/mremi/Flowdock)
- [SDK](https://github.com/flim/PHPFlow)
- [SDK](https://bitbucket.org/j00bar/python-flowdock)
- [SDK](https://github.com/Aeron/PyFlowdock)
- [SDK](https://github.com/hrbrmstr/flowdockr)
- [SDK](https://github.com/gphat/net-flowdock)
- [SDK](https://github.com/samvtran/p5-Flowdock)

## Maintainers

**FN:** API Evangelist
**URL:** https://apievangelist.com
