# ImageKit (imagekit)

ImageKit is a real-time image and video optimization CDN with a REST API for media management, transformations, folder operations, and performance analytics. It provides a unified URL-based API with 50+ transformations, intelligent format optimization (WebP, AVIF), compression, and an integrated Digital Asset Management (DAM) platform for managing and delivering media at scale. ImageKit supports server-side and client-side file uploads, cache management, custom metadata fields, and AI-powered extensions such as background removal and smart cropping.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/imagekit/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/imagekit/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=imagekit-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=imagekit-api-evangelist&utm_content=repo)

## Tags

Images, Video, CDN, Media, Optimization, Transformations, Digital Asset Management, DAM, Storage, Cache, Upload

## APIs

- **ImageKit Media API** - REST API for file uploads, media library management, metadata retrieval, cache purging, custom metadata fields, and account usage. Authentication via HTTP Basic Auth using your private API key. Docs: [https://imagekit.io/docs/api-overview](https://imagekit.io/docs/api-overview)

## Plans, Rate Limits, and FinOps

- **Plans**: [plans/imagekit-plans-pricing.yml](plans/imagekit-plans-pricing.yml) — Four tiers: Forever Free ($0), Lite ($9/mo), Pro ($89/mo), Enterprise (custom). Separate DAM-only plans also available.
- **Rate Limits**: [rate-limits/imagekit-rate-limits.yml](rate-limits/imagekit-rate-limits.yml) — Two-tier system: burst (~100 req/sec) and sustained (40 req/sec reads, 5–20 req/sec writes), enforced at account level. HTTP 429 with X-RateLimit-Reset header on breach.
- **FinOps**: [finops/imagekit-finops.yml](finops/imagekit-finops.yml) — Cost dimensions: bandwidth, storage, VPUs, extension units, user seats, and custom domains. Key optimization: enable automatic WebP/AVIF conversion to reduce bandwidth spend.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | [https://imagekit.io/](https://imagekit.io/) |
| Documentation | [https://imagekit.io/docs](https://imagekit.io/docs) |
| GitHub | [https://github.com/imagekit-developer](https://github.com/imagekit-developer) |
| LinkedIn | [https://www.linkedin.com/company/imagekit-io](https://www.linkedin.com/company/imagekit-io) |
| Blog | [https://imagekit.io/blog/](https://imagekit.io/blog/) |
| Pricing | [https://imagekit.io/plans/](https://imagekit.io/plans/) |
| Status Page | [https://imagekitio.statuspage.io/](https://imagekitio.statuspage.io/) |
| X (Twitter) | [https://twitter.com/ImagekitIo](https://twitter.com/ImagekitIo) |

## Maintainers

- **Kin Lane** - [kin@apievangelist.com](mailto:kin@apievangelist.com)
