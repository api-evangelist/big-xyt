# big xyt (big-xyt)

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

big xyt AG (now branded simply xyt, with big-xyt.com redirecting to xyt.one) is an independent, majority employee-owned market data analytics firm headquartered in Frankfurt am Main, Germany. It sells tick-data-driven market intelligence covering equities, ETFs, listed derivatives, FX, and fixed income across 120+ venues, processing 12bn+ messages per day with roughly ten years of history at nanosecond precision and market-by-order granularity. Products include the Liquidity Cockpit, Transaction Cost Analysis against its SMART benchmark, pre-trade cost modeling, a Datashop of analysis-ready datasets and APIs, and an xyt AI natural-language query layer. Three API products are publicly named — the big xyt API, Liquidity Cockpit API, and TCA API — but their reference documentation sits behind a login at docs.big-xyt.com (HTTP 403 unauthenticated), and access is sales-gated via a book-a-demo motion with no self-serve signup, public pricing, or public OpenAPI.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/big-xyt/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/big-xyt/refs/heads/main/apis.yml)

## Tags

- Financial
- Market Data
- Tick Data
- Trading
- Analytics
- Equities
- ETFs
- Transaction Cost Analysis
- Liquidity
- Order Book

## Timestamps

- **Created:** 2026-07-21
- **Modified:** 2026-07-21

## APIs

### big xyt API

The core big xyt (xyt hub) API gives trading firms and exchanges programmatic access to normalised and raw tick data and analytics across 120+ venues without in-house tick data infrastructure. Publicly listed on the xythub.github.io landing page, but the reference documentation at docs.big-xyt.com is login-gated (HTTP 403 unauthenticated), so endpoints and base URLs are not publicly documented. Legacy public docs (2018, github.com/xythub) described an HTTPS REST service using OAuth 2.0 password-grant bearer tokens with Protocol Buffers payloads and official Python, R, Java, and C# client libraries.

- **Human URL:** [https://docs.big-xyt.com/en/api/api](https://docs.big-xyt.com/en/api/api)

#### Tags

- Tick Data
- Market Data
- Analytics

#### Properties

- [Documentation](https://docs.big-xyt.com/en/api/api) (login-gated)
- [Portal](https://xythub.github.io/)

### Liquidity Cockpit API

API access to the Liquidity Cockpit, big xyt's dark and lit liquidity, market share, and market quality analytics for navigating fragmented equity market structure. Publicly named on the xythub.github.io landing page with a product site at liquidity-cockpit.com, but the API reference at docs.big-xyt.com is login-gated (HTTP 403 unauthenticated), so no endpoints or base URL are publicly documented.

- **Human URL:** [https://docs.big-xyt.com/en/security-analytics/api](https://docs.big-xyt.com/en/security-analytics/api)

#### Tags

- Liquidity
- Market Share
- Equities

#### Properties

- [Documentation](https://docs.big-xyt.com/en/security-analytics/api) (login-gated)
- [Website](https://liquidity-cockpit.com/)

### TCA API

Execution analytics API spanning basic Transaction Cost Analysis — benchmarking trades and orders for best execution, compliance, and client reporting — through full API access to quantitative modelling functions for exchanges and sell-side and buy-side analysts. Publicly named on the xythub.github.io landing page, but the API reference at docs.big-xyt.com is login-gated (HTTP 403 unauthenticated), so no endpoints or base URL are publicly documented.

- **Human URL:** [https://docs.big-xyt.com/en/execution-analytics/api](https://docs.big-xyt.com/en/execution-analytics/api)

#### Tags

- Transaction Cost Analysis
- Execution Analytics
- Best Execution

#### Properties

- [Documentation](https://docs.big-xyt.com/en/execution-analytics/api) (login-gated)

## Common Properties

- [Website](https://xyt.one/)
- [Portal](https://xythub.github.io/)
- [Documentation](https://docs.big-xyt.com/) (login-gated)
- [GitHub Organization](https://github.com/xythub)
- [LinkedIn](https://www.linkedin.com/company/big-xyt/)
- [Blog](https://xyt.one/insights)
- [Privacy Policy](https://xyt.one/privacy-policy)
- [Support](https://xythub.github.io/support.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
