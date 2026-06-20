# Chatbase (chatbase)

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
