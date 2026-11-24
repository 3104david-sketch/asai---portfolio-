# ASAI | AI Receptionist & After-Hours Lead Capture

> **Portfolio case study · Documentation-only · Original source remains private**

An AI-powered after-hours call-handling and lead-capture workflow designed for service businesses, combining conversational intake, webhooks, and notifications.

## The problem
Service businesses can miss inquiries outside office hours and may lack a consistent way to capture the information needed for follow-up.

## My contribution
Product concept, workflow design, business use case, and iterative AI-assisted application development. I used AI coding assistance alongside practical testing and product decisions; I do not claim to have manually written every line of the private implementation.

## How it works
1. Caller reaches an after-hours conversational voice agent.
2. The agent collects necessary request and contact details.
3. A webhook transfers the structured intake event to a lead-capture service.
4. The service records the request and sends a notification for human follow-up.

## Architecture and technical approach
Voice provider events enter a Node.js/Express webhook intake service. The application supports structured lead storage and email notifications; the human team remains responsible for follow-up.

**Technologies:** TypeScript · Node.js · Express · Vapi voice agent integration · Nodemailer · Webhooks · Automation integrations.

## Why it matters to AI marketing
Designed to reduce missed after-hours inquiries and standardize lead intake. Reported client results require separate verification.

## Project status and limitations
**Status:** The private source includes demo infrastructure for voice-agent webhook intake, lead storage, email notifications, and tests. This showcase does not document or independently verify current client deployments.

- No real recordings or customer records made public.
- No production endpoint, secrets or live credentials included.
- Client acquisition and time-saving figures are not independently validated here.

## Explore the project without screenshots
Read [WORKFLOW.md](WORKFLOW.md) for a step-by-step, text-only case study and [PROJECT_FACTS.json](PROJECT_FACTS.json) for structured project metadata. No screenshots, recordings, customer data, or deployable application code are included in this portfolio repository.

## Privacy and scope
This showcase was written independently from the original private repository. It shares high-level architecture and documented functionality only. It does **not** contain original production source, API keys, customer lists, call transcripts, internal pricing, environment files, or original Git history. See [SECURITY.md](SECURITY.md).

## Contact and project ownership
**Benjamin Jackson** — [GitHub profile](https://github.com/3104david-sketch) · AI marketing automation, applied AI systems, and growth operations.
