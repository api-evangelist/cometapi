# CometAPI (cometapi)

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

CometAPI is an AI API aggregator that consolidates access to 500+ models from multiple providers (OpenAI, Anthropic, Google, xAI, DeepSeek, Alibaba, and more) behind a single OpenAI-compatible REST surface. It supports chat completions, embeddings, image generation, text-to-video and image-to-video, speech synthesis, and audio transcription. CometAPI positions itself as a drop-in replacement for the OpenAI SDK (changing only the base URL and key), with pay-as-you-go pricing reportedly 20-40% cheaper than direct vendor rates, sub-400ms median latency, and 99.9% service availability.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cometapi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cometapi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI
- Aggregator
- Audio
- Chat
- Embeddings
- Generative AI
- Images
- LLM
- Multi-Model
- OpenAI-Compatible
- Video

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### CometAPI Unified API

OpenAI-compatible REST API exposing chat completions, embeddings, image generation, video generation, speech synthesis, and audio transcription across hundreds of upstream models. Authentication uses a bearer token, and the `model` field on each request selects the upstream provider (e.g. gpt-5.5, claude-4-7-opus, gemini-2.5-pro, deepseek-v4, sora, veo, kling, whisper).

- **Human URL:** [https://apidoc.cometapi.com/](https://apidoc.cometapi.com/)
- **Base URL:** `https://api.cometapi.com/v1`

#### Tags

- AI
- Aggregator
- Chat
- Embeddings
- Images
- OpenAI-Compatible
- Video

#### Properties

- [Documentation](https://apidoc.cometapi.com/)
- [Marketing](https://www.cometapi.com/)
- [OpenAPI](openapi/cometapi-unified-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cometapi-unified-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cometapi-unified-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/CometAPI-dev)
- [LinkedIn](https://www.linkedin.com/company/cometapi)
- [Website](https://www.cometapi.com/)
- [Documentation](https://apidoc.cometapi.com/)
- [Help Center](https://apidoc.cometapi.com/help-center)
- [Getting Started](https://apidoc.cometapi.com/how-to-use-cometapi-1792005m0)
- [JSON-LD](json-ld/cometapi-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/cometapi-chat-completion-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/cometapi-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [L L Ms Txt](https://www.cometapi.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
