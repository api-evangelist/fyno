# Fyno (fyno)

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

Fyno is a notification routing and orchestration platform that provides a single unified REST API for sending and managing notifications across 10+ communication channels including email, SMS, push, WhatsApp, in-app, RCS, voice, and iMessage. Engineering teams integrate once to gain access to 100+ pre-built provider integrations, a no-code workflow builder, and an advanced routing engine with automated throttling. The platform provides detailed analytics, delivery tracking, user profile management, suppression lists, and campaign management capabilities with a 99.99% uptime SLA.

APIs.json: https://raw.githubusercontent.com/api-evangelist/fyno/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=fyno-api-evangelist&utm_content=repo

## Tags

- Notifications
- Messaging
- Communication
- Push Notifications
- Email
- SMS
- WhatsApp
- In-App
- Orchestration
- Multi-Channel

## APIs

| API | Description | Human URL |
|-----|-------------|-----------|
| Fyno Notification Events API | Core REST API for triggering notification events to single or multiple users across all configured channels. Supports idempotent requests and bulk batch sending. | https://fyno.io/docs/notification-event-creation |
| Fyno User Profiles API | REST API for creating, reading, updating, and deleting user profiles and managing channel-specific destination data. | https://fyno.io/docs/home |
| Fyno User Subscriptions API | REST API for managing user notification preferences and per-channel opt-in/opt-out controls. | https://fyno.io/docs/home |
| Fyno Suppression List API | REST API for managing the global suppression list to prevent notifications to opted-out users. | https://fyno.io/docs/home |
| Fyno Verify API | OTP and TOTP-based verification API for authenticating users via SMS, email, or authenticator apps. | https://fyno.io/docs/home |

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/fyno-plans-pricing.yml](plans/fyno-plans-pricing.yml) |
| Rate Limits | [rate-limits/fyno-rate-limits.yml](rate-limits/fyno-rate-limits.yml) |
| FinOps | [finops/fyno-finops.yml](finops/fyno-finops.yml) |

### Plan Summary

| Plan | Price (USD/year) | Monthly API Requests | Overage per 1M |
|------|-----------------|---------------------|----------------|
| Free Trial | $0 (14 days) | 50,000 (trial total) | N/A |
| Starter | $3,000 | 200,000 | $75 |
| Growth | $8,000 | 800,000 | $55 |
| Business | $25,000 | 3,500,000 | $40 |
| Enterprise | $60,000+ | 12,500,000+ | $30 |

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://fyno.io/ |
| Documentation | https://fyno.io/docs/home |
| API Reference | https://fyno.io/docs/api-reference |
| GitHub Organization | https://github.com/fynoio |
| LinkedIn | https://in.linkedin.com/company/fyno-io |
| X (Twitter) | https://x.com/fynohq |
| Blog | https://fyno.io/blog |
| Pricing | https://fyno.io/ratecard |
| Status Page | https://status.fyno.io/ |
| Changelog | https://fyno.io/docs/release-notes |

## Maintainers

- Kin Lane / kin@apievangelist.com
