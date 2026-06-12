# Fyno (fyno)

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
