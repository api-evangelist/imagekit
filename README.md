# ImageKit (imagekit)

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
