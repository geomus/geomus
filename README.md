# Nahuel Daneri

Senior full-stack developer (Node.js, TypeScript, React, AWS serverless), based in Argentina and working remotely. I like backend-heavy systems where several sources have to behave like one: event-driven flows, integrations and internal platforms.

At Flybondi, a low-cost airline, I'm the technical lead of the team behind its internal platforms. I use AI every day to plan and build software. I read every diff.

Open to senior full-stack and backend roles, remote.

## What I've built at Flybondi

- **Refunds engine** on AWS serverless (SQS + Lambda, idempotent handlers, retries with backoff): about 1,000 bookings per minute, replacing a manual process.
- **Notifications system**, event-driven, with duplicate control through DynamoDB conditional writes and a WhatsApp channel with SMS fallback.
- **GraphQL BFF** (Apollo) serving the booking UI, OTAs and the chatbot, with API-key-scoped operations.
- **Design system** for the whole company, built from scratch (React, Vanilla Extract, Storybook).
- **Payments**: MercadoPago and Worldpay integrations, and a CyberSource fraud-prevention flow I built from scratch.

## Public work

- [mf-zephyr-demo](https://github.com/geomus/mf-zephyr-demo): Module Federation host and remote deployed with Zephyr Cloud (React 19, Rspack, strict TypeScript). It was my first time with both, so the repo keeps a friction log and a note on how I used AI.
- [checkbox-detection-service](https://github.com/geomus/checkbox-detection-service): a take-home that detects filled and unfilled checkboxes in scanned documents (Hono on Lambda, Python and OpenCV, Serverless Framework). Textract is an opt-in alternative behind the same interface, and the decisions are written down as ADRs.
- [surco-ai](https://github.com/geomus/surco-ai): MiCampo, an AI copilot for farmers that combines weather, satellite vegetation data and sales contracts, built at the Shippear 3 hackathon (Next.js, AI SDK, Supabase). I planned it and directed v0 and Claude to build it.

## How I work with AI

I work with Claude Code every day, on a setup of my own: a versioned repo with global instructions, skills, subagents and hooks. A piece of work starts with a written contract and a spec, gets a clean-context review at every checkpoint, and ends with an audit and a handoff. The agent never pushes, never deploys and never reads secrets, and permissions and hooks enforce that, not the prompt. I've used it on a real project and it's still evolving.

## Stack

**Daily:** Node.js, TypeScript, React, GraphQL (Apollo), AWS (Lambda, SQS, SNS, EventBridge, DynamoDB, API Gateway, CDK), MySQL, Jest, CircleCI.
**Also:** Playwright, Docker, TanStack Query.
**Picked up recently, in take-homes and side projects:** Next.js, Hono, PostgreSQL, Module Federation, Vitest.

## Contact

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0e76a8?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/nahueldaneri/)
[![Email](https://img.shields.io/badge/-Email-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:nahuel.daneri@outlook.com)
