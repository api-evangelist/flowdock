# Flowdock (Discontinued) (flowdock)

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
