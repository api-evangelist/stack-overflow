# Stack Overflow (stack-overflow)

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
