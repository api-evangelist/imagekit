# ImageKit GraphQL Schema

## Overview

This is a conceptual GraphQL schema for ImageKit, the real-time image and video optimization CDN and Digital Asset Management (DAM) platform. ImageKit does not currently expose a public GraphQL API; its primary API surface is REST-based (documented at https://imagekit.io/docs/api-overview). This schema is authored to represent the domain model that ImageKit's REST API covers, enabling GraphQL-native tooling, federation overlays, and exploratory integrations.

## Domain Coverage

The schema models the following ImageKit capability areas:

- **Media Library** — files, folders, file versions, tags, and AI-generated tags
- **Transformations** — transformation chains, parameters, effects, crops, overlays, and text rendering
- **Format and Quality** — output format selection, quality presets, and encoding settings
- **URL Generation** — signed and unsigned URL construction for images, videos, and audio
- **Storage** — buckets, managed folders, and branch management
- **Cache** — cache purge requests and CDN cache status
- **Bulk Operations** — batch moves, deletes, tag assignments, and copies
- **Metadata** — EXIF data, pHash, BlurHash, dominant color, and custom metadata fields
- **Media Collections** — logical groupings of assets
- **Webhooks** — event subscription configuration
- **Usage and Quota** — bandwidth consumption, API call counts, storage quota, and dashboard summaries

## Schema Source

- Source type: Conceptual (hand-authored)
- Based on: https://imagekit.io/docs/api-overview and https://docs.imagekit.io/api-reference
- GitHub reference: https://github.com/imagekit-developer
- GraphQL endpoint tested: https://api.imagekit.io/graphql (no response — endpoint does not exist)

## Types Summary

| Category | Types |
|---|---|
| Media Library | File, FileVersion, Folder, Tag, AITag, ManagedFolder, Branch, MediaCollection |
| Transformations | Transformation, TransformationParam, Effect, Crop, Gravity, Focus, Overlay, Text, TextStyle |
| Format / Quality | Format, Quality |
| Color / Visual | Color, Background, Border, BlurHash, DominantColor |
| URLs | URL, ImageURL, VideoURL, AudioURL |
| Storage | Bucket, Size, Width, Height |
| Metadata | EXIF, Phash, CustomMetadata, MetadataKey, CustomField |
| Operations | BulkOperation, Cache, Purge |
| Account | Webhook, Usage, Bandwidth, Quota, Dashboard, Asset |
| Scalars | DateTime, JSON, Upload |

Total: 50+ named types
