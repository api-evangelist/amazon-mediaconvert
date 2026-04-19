# Amazon MediaConvert (amazon-mediaconvert)
AWS Elemental MediaConvert is a file-based video transcoding service that allows you to easily create video-on-demand (VOD) content for broadcast and multiscreen delivery at scale. It supports broadcast-grade features including graphic overlays, content protection, multi-language audio, closed captioning, and a comprehensive range of video formats.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-mediaconvert/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Broadcasting, Media Processing, Media

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon MediaConvert API
AWS Elemental MediaConvert is a file-based video transcoding service that allows you to easily create video-on-demand (VOD) content for broadcast and multiscreen delivery at scale. It supports broadcast-grade features including graphic overlays, content protection, multi-language audio, closed captioning, and a comprehensive range of video formats.

**Human URL:** [https://aws.amazon.com/mediaconvert/](https://aws.amazon.com/mediaconvert/)

#### Tags:

 - Broadcasting, Media Processing, Media

#### Properties

- [Documentation](https://docs.aws.amazon.com/mediaconvert/)
- [OpenAPI](openapi/amazon-mediaconvert-openapi-original.yml)
- [GettingStarted](https://aws.amazon.com/mediaconvert/getting-started/)
- [Pricing](https://aws.amazon.com/mediaconvert/pricing/)
- [FAQ](https://aws.amazon.com/mediaconvert/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/mediaconvert/)
- [Documentation](https://docs.aws.amazon.com/mediaconvert/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/media/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/mediaconvert/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Broadcast-Grade Video Processing | Graphic overlays, content protection, multi-language audio, closed captioning, and professional broadcast formats. |
| Comprehensive Format Support | Supports AVC, HEVC, AV1, Apple ProRes, MPEG-2, CMAF, HLS, DASH ISO, Smooth Streaming, 4K, 8K, and HDR including Dolby Vision. |
| Automated Infrastructure Management | Automates workload provisioning, scaling, monitoring, and resource optimization without manual server management. |
| Built-in Reliability | Jobs run on redundant infrastructure across multiple Availability Zones with automatic health monitoring and failover. |
| Job Templates and Presets | Create reusable job templates and output presets to standardize and accelerate video transcoding workflows. |
| Queue Management | Organize and prioritize transcoding jobs using on-demand and reserved queues. |

## Use Cases

| Name | Description |
|------|-------------|
| VOD Content Production | Transcode video files for video-on-demand delivery at broadcast quality. |
| Large Library Transcoding | Process large content libraries for multiscreen delivery at any scale. |
| Broadcast Distribution | Create broadcast-format outputs for television and streaming platform distribution. |
| Peak Workload Processing | Handle variable transcoding workloads with elastic auto-scaling. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Use S3 for input and output storage of video files. |
| AWS Elemental MediaPackage | Package transcoded outputs for adaptive bitrate streaming delivery. |
| Amazon CloudWatch | Monitor job metrics and set alerts for transcoding workflows. |
| Amazon EventBridge | Trigger downstream workflows based on MediaConvert job state changes. |
| AWS IAM | Control access to MediaConvert resources and S3 buckets using IAM roles. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon MediaConvert OpenAPI](openapi/amazon-mediaconvert-openapi-original.yml)

### JSON Schema

- 633 schema files in [json-schema/](json-schema/)

### JSON Structure

- 633 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Amazon MediaConvert API Context](json-ld/amazon-mediaconvert-mediaconvert-api-context.jsonld)

### Examples

- 633 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon MediaConvert](capabilities/shared/mediaconvert.yaml) — 28 operations for media processing

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon MediaConvert Workflow](capabilities/amazon-mediaconvert-media-workflow.yaml) | Amazon MediaConvert | 8 | Broadcast Engineer |

## Vocabulary

- [Amazon MediaConvert Vocabulary](vocabulary/amazon-mediaconvert-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon MediaConvert Spectral Rules](rules/amazon-mediaconvert-spectral-rules.yml) — 20 rules across 8 categories enforcing Amazon MediaConvert API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
