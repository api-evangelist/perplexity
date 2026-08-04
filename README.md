# Perplexity (perplexity)

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

Perplexity AI is an answer engine that delivers accurate answers to complex questions using large language models with real-time web search capabilities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/perplexity/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/perplexity/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Timestamps

- **Created:** 2025-02-21
- **Modified:** 2026-05-29

## APIs

### Perplexity

What do you want to know?

- **Human URL:** [ https://www.perplexity.ai/]( https://www.perplexity.ai/)

#### Properties

- [Documentation]( https://www.perplexity.ai/)
- [Postman Collection](collections/perplexity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perplexity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Perplexity Sonar API

The Sonar API provides access to Perplexity's Sonar family of models including sonar, sonar-pro, sonar-reasoning-pro, and sonar-deep-research via an OpenAI-compatible chat completions endpoint with built-in web search grounding.

- **Human URL:** [https://docs.perplexity.ai/docs/sonar/quickstart](https://docs.perplexity.ai/docs/sonar/quickstart)
- **Base URL:** `https://api.perplexity.ai`

#### Tags

- Artificial Intelligence
- Chat Completions
- Grounding
- Large Language Models
- Search

#### Properties

- [Documentation](https://docs.perplexity.ai/docs/sonar/quickstart)
- [API Reference](https://docs.perplexity.ai/api-reference/chat-completions-post)
- [Authentication](https://docs.perplexity.ai/guides/api-key-management)
- [Pricing](https://docs.perplexity.ai/docs/getting-started/pricing)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/perplexity/refs/heads/main/openapi/perplexity-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/perplexity/refs/heads/main/asyncapi/perplexity-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/perplexity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perplexity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Perplexity Async Chat Completions API

The Async Chat Completions API enables developers to submit long-running chat completion requests for background processing. Requests are queued and processed asynchronously, returning a unique identifier for tracking status through creation, processing, completion, or failure stages, making it ideal for deep research and computationally intensive queries.

- **Human URL:** [https://docs.perplexity.ai/api-reference/async-chat-completions-post](https://docs.perplexity.ai/api-reference/async-chat-completions-post)
- **Base URL:** `https://api.perplexity.ai`

#### Tags

- Artificial Intelligence
- Asynchronous
- Chat Completions
- Large Language Models

#### Properties

- [Documentation](https://docs.perplexity.ai/api-reference/async-chat-completions-post)
- [API Reference](https://docs.perplexity.ai/api-reference/async-chat-completions-get)
- [Authentication](https://docs.perplexity.ai/guides/api-key-management)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/perplexity/refs/heads/main/asyncapi/perplexity-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/perplexity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perplexity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Perplexity Search API

The Search API enables developers to perform ranked web searches with advanced filtering including domain, language, country, and date recency controls, returning structured results with titles, URLs, snippets, and publication dates.

- **Human URL:** [https://docs.perplexity.ai/guides/search-quickstart](https://docs.perplexity.ai/guides/search-quickstart)
- **Base URL:** `https://api.perplexity.ai`

#### Tags

- Filtering
- Ranking
- Search
- Web Search

#### Properties

- [Documentation](https://docs.perplexity.ai/guides/search-quickstart)
- [API Reference](https://docs.perplexity.ai/api-reference/search-post)
- [Authentication](https://docs.perplexity.ai/guides/api-key-management)
- [Best  Practices](https://docs.perplexity.ai/guides/search-best-practices)
- [Postman Collection](collections/perplexity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perplexity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Perplexity Responses API

The Responses API (Agentic Research API) provides access to third-party frontier models from providers like OpenAI, Anthropic, Google, and xAI with integrated web search tools, URL fetching, function calling, and multi-step reasoning presets such as pro-search and deep-research.

- **Human URL:** [https://docs.perplexity.ai/docs/grounded-llm/responses/quickstart](https://docs.perplexity.ai/docs/grounded-llm/responses/quickstart)
- **Base URL:** `https://api.perplexity.ai`

#### Tags

- Agents
- Artificial Intelligence
- Large Language Models
- Research
- Web Search

#### Properties

- [Documentation](https://docs.perplexity.ai/docs/grounded-llm/responses/quickstart)
- [API Reference](https://docs.perplexity.ai/api-reference/responses-post)
- [Authentication](https://docs.perplexity.ai/guides/api-key-management)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/perplexity/refs/heads/main/asyncapi/perplexity-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/perplexity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perplexity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Perplexity Embeddings API

The Embeddings API generates high-quality text embeddings for semantic search and retrieval, offering both standard embeddings for independent texts and contextualized embeddings for document chunks that share context, with support for Matryoshka representation learning for flexible dimensionality.

- **Human URL:** [https://docs.perplexity.ai/docs/embeddings/quickstart](https://docs.perplexity.ai/docs/embeddings/quickstart)
- **Base URL:** `https://api.perplexity.ai`

#### Tags

- Embeddings
- Retrieval
- Semantic Search
- Vectors

#### Properties

- [Documentation](https://docs.perplexity.ai/docs/embeddings/quickstart)
- [API Reference](https://docs.perplexity.ai/api-reference/embeddings-post)
- [Authentication](https://docs.perplexity.ai/guides/api-key-management)
- [Best  Practices](https://docs.perplexity.ai/docs/embeddings/best-practices)
- [Postman Collection](collections/perplexity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perplexity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/perplexity-ai)
- [Getting Started](https://docs.perplexity.ai/docs/getting-started)
- [API Reference](https://docs.perplexity.ai/reference/post_chat_completions)
- [Models](https://docs.perplexity.ai/docs/model-cards)
- [Pricing](https://docs.perplexity.ai/docs/pricing)
- [Terms of Service](https://www.perplexity.ai/hub/terms)
- [Privacy Policy](https://www.perplexity.ai/hub/privacy)
- [Blog](https://www.perplexity.ai/hub/blog)
- [Quickstart](https://docs.perplexity.ai/docs/getting-started/quickstart)
- [Pricing  Page](https://docs.perplexity.ai/docs/getting-started/pricing)
- [Model  Directory](https://docs.perplexity.ai/docs/getting-started/models)
- [Changelog](https://docs.perplexity.ai/docs/resources/changelog)
- [Product  Change  Log](https://www.perplexity.ai/changelog)
- [Rate Limits](https://docs.perplexity.ai/guides/usage-tiers)
- [Sign Up](https://perplexity.ai/account/api)
- [Dashboard](https://www.perplexity.ai/account/api/group)
- [A P I  Playground](https://perplexity.ai/account/api/playground/search)
- [S D Ks](https://docs.perplexity.ai/guides/perplexity-sdk)
- [Git Hub  Org](https://github.com/perplexityai)
- [Python  S D K](https://github.com/perplexityai/perplexity-py)
- [Best  Practices](https://docs.perplexity.ai/guides/search-best-practices)
- [M C P  Server](https://docs.perplexity.ai/guides/mcp-server)
- [Support](https://www.perplexity.ai/help-center/en)
- [Forum](https://community.perplexity.ai)
- [Portal](https://www.perplexity.ai/api-platform)
- [L L Ms  T X T](https://docs.perplexity.ai/llms.txt)
- [Website](https://www.perplexity.ai)
- [Documentation](https://docs.perplexity.ai)
- [Authentication](https://docs.perplexity.ai/guides/api-key-management)
- [Status Page](https://status.perplexity.com)
- [Roadmap](https://docs.perplexity.ai/feature-roadmap)
- [Cookbook](https://docs.perplexity.ai/docs/cookbook)
- [Prompt  Guide](https://docs.perplexity.ai/guides/prompt-guide)
- [Structured  Outputs  Guide](https://docs.perplexity.ai/guides/structured-outputs)
- [Performance  Guide](https://docs.perplexity.ai/guides/perplexity-sdk-performance)
- [Date  Range  Filter  Guide](https://docs.perplexity.ai/guides/date-range-filter-guide)
- [Academic  Filter  Guide](https://docs.perplexity.ai/guides/academic-filter-guide)
- [Crawlers](https://docs.perplexity.ai/docs/resources/perplexity-crawlers)
- [A P I  Terms of  Service](https://www.perplexity.ai/hub/legal/perplexity-api-terms-of-service)
- [Discussions](https://docs.perplexity.ai/discussions/discussions)
- [Discord](https://discord.com/invite/perplexity-ai)
- [X (Twitter)](https://x.com/perplexity_ai)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**FN:** Perplexity AI
**Email:** support@perplexity.ai
**URL:** https://www.perplexity.ai
