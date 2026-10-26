# Stack Overflow (stack-overflow)

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

Stack Overflow is the world's largest question-and-answer community for developers, with over 23 million questions on programming, software development, and technology topics. Stack Overflow offers two API products: the public Stack Exchange API v2.3 for read/write access to Stack Overflow questions, answers, comments, users, tags, and badges; and the Stack Overflow for Teams API v3, a private team knowledge-base API with endpoints for questions, answers, articles, user groups, and SME management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/stack-overflow/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/stack-overflow/refs/heads/main/apis.yml)

## Tags

- Answers
- Code
- Developer Community
- Developer Tools
- Knowledge Base
- Programming
- Q&A
- Questions
- Stack Overflow

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### Stack Overflow API

The Stack Overflow public API (v2.3) provides programmatic access to questions, answers, comments, users, tags, and badges on the Stack Overflow site. Developers can read and write content with OAuth 2.0 authentication. The API returns JSON responses with a standard wrapper envelope that includes pagination, quota, and backoff metadata. Register an application at StackApps to obtain OAuth credentials.

- **Human URL:** [https://api.stackexchange.com/](https://api.stackexchange.com/)
- **Base URL:** `https://api.stackexchange.com/2.3`

#### Tags

- Answers
- Badges
- Comments
- Developer Community
- Q&A
- Questions
- Stack Overflow
- Users

#### Properties

- [Documentation](https://api.stackexchange.com/docs)
- [Terms of Service](https://stackexchange.com/legal/api-terms-of-use)
- [Rate Limits](https://api.stackexchange.com/docs/throttle)
- [Sign Up](http://stackapps.com/apps/oauth/register)
- [OpenAPI](openapi/stack-overflow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/stack-overflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stack-overflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stack Overflow for Teams API v3

The Stack Overflow for Teams API v3 provides read and write access to private team knowledge bases. It supports managing questions, answers, articles, user groups, subject matter experts (SMEs), and tags within a Stack Overflow for Teams instance. The API uses Personal Access Token (PAT) authentication via the Authorization Bearer header. Business tier subscriptions have read/write access; Basic tier has read-only access.

- **Human URL:** [https://api.stackoverflowteams.com/docs](https://api.stackoverflowteams.com/docs)
- **Base URL:** `https://api.stackoverflowteams.com/v3`

#### Tags

- Articles
- Enterprise
- Knowledge Management
- Q&A
- Stack Overflow
- Teams

#### Properties

- [Documentation](https://api.stackoverflowteams.com/docs)
- [Blog](https://stackoverflow.blog/2023/05/17/stack-overflow-for-teams-api-v3/)
- [OpenAPI](openapi/stack-overflow-for-teams-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/stack-overflow-for-teams.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stack-overflow-for-teams.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/stackexchange)
- [LinkedIn](https://www.linkedin.com/company/stack-overflow)
- [Website](https://stackoverflow.com)
- [Blog](https://stackoverflow.blog/)
- [Authentication](https://api.stackexchange.com/docs/authentication)
- [Sign Up](http://stackapps.com/apps/oauth/register)
- [Terms of Service](https://stackexchange.com/legal/api-terms-of-use)
- [JSON-LD](json-ld/stack-overflow-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/stack-overflow-question-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](vocabulary/stack-overflow-vocabulary.yml)
- [Spectral Rules](rules/stack-overflow-rules.yml)
