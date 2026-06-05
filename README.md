# CometAPI (cometapi)

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
