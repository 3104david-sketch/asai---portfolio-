# ASAI | AI Receptionist & Lead-Capture Automation

## Overview
An AI-powered after-hours voice and lead-capture workflow for service businesses, designed to collect caller details and notify a human operator for follow-up.

## Features
- Conversational voice-agent flow for after-hours callers
- Webhook intake and structured lead capture
- Email notifications and human escalation
- Lead lifecycle and operational checks
- Demo payloads and test-friendly workflows

## Technical stack
TypeScript, Node.js, Express, Vapi-style webhook integration, Nodemailer, automation platforms and APIs

## Architecture
- Incoming call → conversational AI voice flow
- Voice provider event → validated webhook/lead intake
- Captured lead → notification → human follow-up

## Relevance to AI marketing and operations
Illustrates AI-assisted lead capture, response operations, and reducing missed inquiries outside business hours. Client count and time savings are resume-reported outcomes, not independently audited in this repository.

## Project status and limitations
Project metadata documents an after-hours lead-capture demo, webhook, lead store, email notifier, and test scripts. This showcase does not reproduce the company’s production deployment or client records.

## Public demo and privacy
A synthetic lead event and a mock notification; no real customer details, phone numbers, tokens, or proprietary client configurations.

This is a **new, documentation-only public portfolio showcase** based on a review of selected repository documentation and metadata. It does **not** include or publish the original private source repository, code, customer data, credentials, commit history, or deployable system. Screenshots and video demonstrations may be added only after confirming they contain synthetic or redacted information.

## Authorship and AI-assisted development
Product direction and project ownership: Benjamin Jackson. Development involved AI-assisted coding tools and iterative testing. Do not interpret this showcase as a claim that every line of implementation was personally hand-written.

## Next steps
- Record a short walkthrough with only fictional/test data.
- Add screenshots in `assets/` after visually checking for confidential information.
- Add a verified results section with the measurement period and baseline, where available.
