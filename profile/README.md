<p align="center">
  <img src="https://sendly.live/" alt="Sendly" width="80" />
</p>

<h1 align="center">Sendly</h1>

<p align="center">
  <strong>Simple, powerful SMS API for developers</strong>
</p>

<p align="center">
  <a href="https://sendly.live">Website</a> ·
  <a href="https://sendly.live/docs">Documentation</a> ·
  <a href="https://sendly.live/dashboard">Dashboard</a>
</p>

---

## What is Sendly?

Sendly is an SMS platform built for developers. Send text messages globally with a simple API, transparent pricing, and instant setup.

**Key Features:**
- **Global Reach** — Send to 50+ countries
- **Simple Pricing** — Pay-as-you-go credits, no monthly fees
- **Developer-First** — SDKs for every major language
- **Fast Setup** — Start sending in under 5 minutes
- **Real-time Webhooks** — Delivery status updates instantly

## Official SDKs

| Language | Package | Install |
|----------|---------|---------|
| **Node.js** | [@sendly/sdk](https://github.com/SendlyHQ/sendly-node) | `npm install @sendly/sdk` |
| **Python** | [sendly](https://github.com/SendlyHQ/sendly-python) | `pip install sendly` |
| **Go** | [sendly-go](https://github.com/SendlyHQ/sendly-go) | `go get github.com/SendlyHQ/sendly-go` |
| **Java** | [sendly](https://github.com/SendlyHQ/sendly-java) | Maven Central |
| **Rust** | [sendly](https://github.com/SendlyHQ/sendly-rust) | `cargo add sendly` |
| **Ruby** | [sendly](https://github.com/SendlyHQ/sendly-ruby) | `gem install sendly` |
| **PHP** | [sendly/sendly](https://github.com/SendlyHQ/sendly-php) | `composer require sendly/sendly-php` |
| **.NET** | [Sendly](https://github.com/SendlyHQ/sendly-dotnet) | `dotnet add package Sendly` |
| **CLI** | [@sendly/cli](https://github.com/SendlyHQ/sendly-cli) | `npm install -g @sendly/cli` |

## Quick Start

```bash
# Install
npm install @sendly/sdk

# Send a message
import { Sendly } from '@sendly/sdk';

const sendly = new Sendly('sk_live_v1_your_key');

await sendly.messages.send({
  to: '+15551234567',
  text: 'Hello from Sendly!'
});
```

## Pricing

| Region | Cost |
|--------|------|
| US & Canada | 1 credit/SMS |
| UK, India, Poland | 8 credits/SMS |
| France, Japan, Australia | 12 credits/SMS |
| Germany, Italy, Mexico | 16 credits/SMS |

**$10 = 1,000 credits** · No monthly fees · Credits never expire

## Resources

- [API Reference](https://sendly.live/docs/api)
- [CLI Documentation](https://sendly.live/docs/cli)
- [Webhook Events](https://sendly.live/docs/webhooks)
- [Sandbox Testing](https://sendly.live/docs/sandbox)

## Support

- **Email**: support@sendly.live
- **Issues**: Open an issue in the relevant SDK repo

---

<p align="center">
  <sub>Built with care in San Francisco</sub>
</p>
