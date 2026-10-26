# Global Relay (global-relay)

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

Global Relay is an enterprise-grade archiving and compliance platform for electronic communications including email, instant messaging, voice, video, and collaboration tools across regulated industries. It provides APIs for archiving conversations, emails, voice recordings, and event feeds from social media and collaboration platforms, ensuring organizations meet their compliance and regulatory requirements through secure, tamper-proof archiving with OAuth 2.0 authenticated REST APIs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Archiving
- Compliance
- Data Retention
- Email Security
- Regulatory Compliance

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Global Relay Conversation Archiving API

The Global Relay Conversation Archiving API provides a RESTful interface to seamlessly integrate messaging platforms with the Global Relay Archive. It enables secure capture and preservation of one-to-one or multi-party conversations, including text messages, file attachments, reactions, edits, and deletions. The API uses OAuth 2.0 Client Credentials authentication and is rate limited to 1000 requests per minute for conversations and 100 per minute for files.

- **Human URL:** [https://developers.globalrelay.com/api/conversation-archiving-api/](https://developers.globalrelay.com/api/conversation-archiving-api/)

#### Tags

- Archiving
- Compliance
- Messaging

#### Properties

- [Documentation](https://developers.globalrelay.com/api/conversation-archiving-api/)
- [OpenAPI](openapi/global-relay-conversation-archiving-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/global-relay-conversation-archiving-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/global-relay-conversation-archiving-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Global Relay Email Archiving API

The Global Relay Email Archiving API provides a RESTful interface to capture and archive email content and metadata into the Global Relay Archive. It supports archiving emails with attachments, headers, and full message structure for compliance and regulatory requirements. Rate limited to 1000 requests per minute for emails and 100 per minute for files.

- **Human URL:** [https://developers.globalrelay.com/api/email-archiving-api/](https://developers.globalrelay.com/api/email-archiving-api/)

#### Tags

- Archiving
- Compliance
- Email

#### Properties

- [Documentation](https://developers.globalrelay.com/api/email-archiving-api/)
- [OpenAPI](openapi/global-relay-email-archiving-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/global-relay-email-archiving-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/global-relay-email-archiving-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Global Relay Voice Archiving API

The Global Relay Voice Archiving API provides a RESTful interface to capture and archive audio and video recordings, including call recordings and meeting recordings, into the Global Relay Archive. The API ensures all voice and video communications are securely preserved for compliance. The maximum data payload per request is 3.5MB excluding file attachments.

- **Human URL:** [https://developers.globalrelay.com/api/voice-archiving-api/](https://developers.globalrelay.com/api/voice-archiving-api/)

#### Tags

- Archiving
- Compliance
- Voice

#### Properties

- [Documentation](https://developers.globalrelay.com/api/voice-archiving-api/)
- [OpenAPI](openapi/global-relay-voice-archiving-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/global-relay-voice-archiving-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/global-relay-voice-archiving-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Global Relay Event Archiving API

The Global Relay Event Archiving API (EventFeed) provides a RESTful interface to integrate collaboration platforms, customer experience tools, and social media sites with the Global Relay Archive. It enables secure capture of event-based data including posts, comments, reactions, and activity feeds from various digital channels for compliance archiving.

- **Human URL:** [https://developers.globalrelay.com/api/event-archiving-api/](https://developers.globalrelay.com/api/event-archiving-api/)

#### Tags

- Archiving
- Collaboration
- Compliance
- Social Media

#### Properties

- [Documentation](https://developers.globalrelay.com/api/event-archiving-api/)
- [OpenAPI](openapi/global-relay-event-archiving-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/global-relay-event-archiving-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/global-relay-event-archiving-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/globalrelay)
- [LinkedIn](https://www.linkedin.com/company/global-relay)
- [Portal](https://developers.globalrelay.com/)
- [Documentation](https://www.globalrelay.com/connector/conversation-archiving-api/)
- [Documentation](https://www.globalrelay.com/connector/eventfeed-archiving-api/)
- [Documentation](https://www.globalrelay.com/connector/voice-archiving-api/)
- [L L Ms Txt](https://globalrelay.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
