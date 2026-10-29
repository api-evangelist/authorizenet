# Authorize.net

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Authorize.net is a payment gateway operated by Visa (Visa Acceptance Solutions) that lets merchants and platforms accept credit card and eCheck.Net payments online, in person, and through mobile apps. Its developer platform exposes a transaction API (the XML/JSON gateway at /xml/v1 and a REST surface at /rest/v1) for one-time and recurring payments, the Customer Information Manager (CIM) for stored payment profiles, Accept.js and Accept Hosted for tokenized/hosted card capture, Automated Recurring Billing (ARB), transaction reporting, fraud detection (Advanced Fraud Detection Suite), and webhooks for asynchronous event notifications. Official server SDKs ship for PHP, .NET, Java, Python, Node.js, and Ruby, plus Accept mobile SDKs for iOS and Android. Authentication uses merchant API Login ID + Transaction Key, with OAuth 2.0 available for partner/Accept integrations. Added to the API Evangelist network from an Insight Partners portfolio lead and enriched from Authorize.net's public developer surface.

**Areas:** Company · Payments · Payment Gateway · Credit Cards · E-Commerce · Recurring Billing · Fraud Prevention · Webhook · Financial Services

## Authorize.net on APIs.io

Everything profiled for Authorize.net is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/authorizenet/](https://apis.io/providers/authorizenet/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Authorize.net API](https://apis.io/apis/authorizenet/authorizenet-api/) — Payment gateway API for accepting credit card and eCheck.Net payments, storing customer payment profiles (CIM), recurring billing (ARB), hosted/tokenized…
- [Authorize.net Payment API](https://apis.io/apis/authorizenet/authorize-net-payment-api/) — The Authorize.net Payment API enables merchants to process credit card, debit card, eCheck, Apple Pay, Google Pay, and PayPal transactions via a POST-based…
- [Authorize.net Recurring Billing API](https://apis.io/apis/authorizenet/authorize-net-recurring-billing-api/) — The Authorize.net Automated Recurring Billing (ARB) API enables merchants to create, update, and cancel subscription-based payment schedules for recurring…
- [Authorize.net Customer Profiles API](https://apis.io/apis/authorizenet/authorize-net-customer-profiles-api/) — The Authorize.net Customer Information Manager (CIM) API enables secure storage and management of customer payment profiles including credit cards and bank…
- [Authorize.net Webhooks](https://apis.io/apis/authorizenet/authorize-net-webhooks/) — Authorize.net Webhooks deliver real-time event notifications for transaction, subscription, and fraud management events to merchant-configured HTTP endpoints.
- [Authorize.net Transactions API](https://apis.io/apis/authorizenet/authorizenet-transactions-api/) — Charge, authorize, capture, void and refund transactions.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Authorizenet Webhooks](https://apis.io/asyncapis/authorizenet/authorizenet-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [authorize-net-mcp](https://apis.io/servers/authorizenet/authorize-net-mcp/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Authorizenet Authentication](https://apis.io/security/authorizenet/authorizenet-authentication/)
- [Authorizenet Domain Security](https://apis.io/security/authorizenet/authorizenet-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.authorize.net/)
- [Documentation](https://developer.authorize.net/api/reference/index.html)
- [Getting started](https://developer.authorize.net/hello_world.html)
- [API reference](https://developer.authorize.net/api/reference/index.html)
- [Pricing](https://www.authorize.net/sign-up/pricing.html)
- [Sign up](https://www.authorize.net/sign-up.html)
- [Support](https://developer.authorize.net/support.html)
- [Terms of service](https://www.authorize.net/about-us/terms.html)
- [Privacy policy](https://www.authorize.net/about-us/privacy.html)
- [GitHub](https://github.com/AuthorizeNet)
- [Status](https://status.authorize.net/)

## API Evangelist rating

**Kin Score 34.7** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 8.1 |
| Contract governance | 4.5 |
| Operational transparency | 26.3 |
| Developer ergonomics | 61.9 |
| Access clarity | 44.7 |

**Agent readiness 25.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 29.5** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/authorizenet/](https://apis.io/providers/authorizenet/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Authorize.net: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/authorizenet/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
