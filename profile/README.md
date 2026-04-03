<p align="center">
<img src="https://sendly.live/logo-github.png" alt="Sendly" width="80" />
</p>

<h1 align="center">Sendly</h1>

<p align="center">
  <strong>The SMS API for developers & Agents</strong>
</p>

<p align="center">
  <a href="https://sendly.live">Website</a> ·
  <a href="https://sendly.live/docs">Documentation</a> ·
  <a href="https://sendly.live/dashboard">Dashboard</a>
</p>

---

## What is Sendly?

Sendly is a developer-first SMS and MMS API with built-in compliance, OTP verification, and international reach. Send messages to 190+ countries with a single API call.

**Key Features:**
- **Global Reach** — Send to 190+ countries
- **SMS & MMS** — Text, images, and media
- **Verify API** — Phone verification in 2 API calls
- **Hosted Verification** — Stripe Checkout-style phone auth flow
- **Teams & Enterprise** — Multi-workspace support with pooled credits
- **Campaigns** — Bulk messaging with contact lists and personalization
- **Compliance Built-in** — TCPA quiet hours, opt-out handling, SHAFT filtering
- **Simple Pricing** — Pay-as-you-go credits, no monthly fees
- **Real-time Webhooks** — Delivery status updates instantly

## Official SDKs

| Language | Package | Install |
|----------|---------|---------|
| **Node.js** | [@sendly/node](https://github.com/SendlyHQ/sendly-node) | `npm install @sendly/node` |
| **Python** | [sendly](https://github.com/SendlyHQ/sendly-python) | `pip install sendly` |
| **Go** | [sendly-go](https://github.com/SendlyHQ/sendly-go) | `go get github.com/SendlyHQ/sendly-go/v3` |
| **Java** | [sendly-java](https://github.com/SendlyHQ/sendly-java) | Maven Central |
| **Rust** | [sendly](https://github.com/SendlyHQ/sendly-rust) | `cargo add sendly` |
| **Ruby** | [sendly](https://github.com/SendlyHQ/sendly-ruby) | `gem install sendly` |
| **PHP** | [sendly/sendly-php](https://github.com/SendlyHQ/sendly-php) | `composer require sendly/sendly-php` |
| **.NET** | [Sendly](https://github.com/SendlyHQ/sendly-dotnet) | `dotnet add package Sendly` |
| **CLI** | [@sendly/cli](https://github.com/SendlyHQ/sendly-cli) | `npm install -g @sendly/cli` |

## Quick Start

```javascript
import Sendly from '@sendly/node';

const sendly = new Sendly('sk_live_v1_your_key');

// Send SMS
await sendly.messages.send({
  to: '+15551234567',
  text: 'Hello from Sendly!'
});

// Phone Verification
await sendly.verify.send({ to: '+15551234567' });
await sendly.verify.check({ phone: '+15551234567', code: '123456' });
```

## Pricing

| Region | Cost |
|--------|------|
| US & Canada | 2 credits ($0.02) |
| Tier 1 (UK, AU, BR, etc.) | 8 credits ($0.08) |
| Tier 2 (IN, FR, JP, etc.) | 12 credits ($0.12) |
| Tier 3 (DE, NL, MX, etc.) | 16 credits ($0.16) |
| Tier 4 (VN, SA, UA, etc.) | 24 credits ($0.24) |
| Tier 5 (MY, EG, NG, etc.) | 48 credits ($0.48) |

**$10 = 1,000 credits** · No monthly fees · Credits never expire

## Resources

- [API Reference](https://sendly.live/docs/api-reference)
- [CLI Documentation](https://sendly.live/docs/cli)
- [Webhooks](https://sendly.live/docs/webhooks)
- [Sandbox Testing](https://sendly.live/docs/sandbox)
- [Changelog](https://sendly.live/changelog)

## Support

- **Email**: support@sendly.live
- **Twitter**: [@sendly_live](https://twitter.com/sendly_live)
