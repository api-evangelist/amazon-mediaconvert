# Amazon MediaConvert (amazon-mediaconvert)

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
