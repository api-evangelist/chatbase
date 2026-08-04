# Chatbase (chatbase)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Chatbase is a custom AI chatbot and AI agent platform for customer support. Teams train an agent on their own content (websites, files, Q&A), embed it on their site, and connect it to channels and tools. The Chatbase REST API lets developers message agents (with streaming), create and update chatbots/agents, retrieve conversations and leads, and manage contacts.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/chatbase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/chatbase/refs/heads/main/apis.yml)

## Tags

- AI
- Chatbot
- AI Agent
- Customer Support
- Conversational AI

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Chatbase Chat API

Send a message to a Chatbase agent and receive a response. Accepts a messages array with user and assistant roles, supports continuing an existing conversation, temperature control, and word-by-word streaming via stream=true.

- **Human URL:** [https://www.chatbase.co/docs/developer-guides/api-integration](https://www.chatbase.co/docs/developer-guides/api-integration)
- **Base URL:** `https://www.chatbase.co/api/v1`

#### Tags

- Chat
- Messages
- Streaming

#### Properties

- [Documentation](https://www.chatbase.co/docs/developer-guides/api-integration)
- [API Reference](https://www.chatbase.co/docs/developer-guides/api/chat)
- [OpenAPI](openapi/chatbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chatbase Chatbots and Agents API

Programmatically create chatbots/agents from training text, retrain and rename them, update settings, list all agents on the account, delete an agent, and manage agent icons and profile pictures.

- **Human URL:** [https://www.chatbase.co/docs/developer-guides/api-integration](https://www.chatbase.co/docs/developer-guides/api-integration)
- **Base URL:** `https://www.chatbase.co/api/v1`

#### Tags

- Chatbots
- Agents
- Management

#### Properties

- [Documentation](https://www.chatbase.co/docs/developer-guides/api-integration)
- [API Reference](https://www.chatbase.co/docs/developer-guides/api/create-chatbot)
- [OpenAPI](openapi/chatbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chatbase Conversations API

Retrieve a paginated history of conversations for a specific chatbot, filterable by date range and source, with full message transcripts.

- **Human URL:** [https://www.chatbase.co/docs/developer-guides/api/get-conversations](https://www.chatbase.co/docs/developer-guides/api/get-conversations)
- **Base URL:** `https://www.chatbase.co/api/v1`

#### Tags

- Conversations
- History
- Transcripts

#### Properties

- [Documentation](https://www.chatbase.co/docs/developer-guides/api/get-conversations)
- [API Reference](https://www.chatbase.co/docs/developer-guides/api/get-conversations)
- [OpenAPI](openapi/chatbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chatbase Sources and Data API

Update and retrain an agent with new training content, and manage contacts and their custom-attribute schema for a chatbot (create, list, get, update, and delete contacts and custom attributes).

- **Human URL:** [https://www.chatbase.co/docs/developer-guides/api-integration](https://www.chatbase.co/docs/developer-guides/api-integration)
- **Base URL:** `https://www.chatbase.co/api/v1`

#### Tags

- Sources
- Training Data
- Contacts

#### Properties

- [Documentation](https://www.chatbase.co/docs/developer-guides/api-integration)
- [API Reference](https://www.chatbase.co/docs/developer-guides/api/update-chatbot-data)
- [OpenAPI](openapi/chatbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chatbase Leads API

Retrieve leads collected by a chatbot's lead-capture form for a specific chatbot, returning name, email, phone, and submission metadata.

- **Human URL:** [https://www.chatbase.co/docs/developer-guides/api/get-leads](https://www.chatbase.co/docs/developer-guides/api/get-leads)
- **Base URL:** `https://www.chatbase.co/api/v1`

#### Tags

- Leads
- Capture
- CRM

#### Properties

- [Documentation](https://www.chatbase.co/docs/developer-guides/api/get-leads)
- [API Reference](https://www.chatbase.co/docs/developer-guides/api/get-leads)
- [OpenAPI](openapi/chatbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/chatbase)
- [LinkedIn](https://www.linkedin.com/company/chatbase)
- [Website](https://www.chatbase.co)
- [Documentation](https://www.chatbase.co/docs)
- [Plans](plans/chatbase-plans-pricing.yml)
- [Rate Limits](rate-limits/chatbase-rate-limits.yml)
- [Fin Ops](finops/chatbase-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
