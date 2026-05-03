# Stack Overflow

Stack Overflow is the world's largest question-and-answer community for developers, with over 23 million questions on programming, software development, and technology topics. Stack Overflow offers two API products: the public Stack Exchange API v2.3 for read/write access to Stack Overflow questions, answers, comments, users, tags, and badges; and the Stack Overflow for Teams API v3, a private team knowledge-base API with endpoints for questions, answers, articles, user groups, and SME management.

## Tags

Answers, Code, Developer Community, Developer Tools, Knowledge Base, Programming, Q&A, Questions, Stack Overflow

## APIs

### Stack Overflow API

The Stack Overflow public API (v2.3) provides programmatic access to questions, answers, comments, users, tags, and badges on the Stack Overflow site. Developers can read and write content with OAuth 2.0 authentication. Register an application at StackApps to obtain OAuth credentials.

**Human URL:** [https://api.stackexchange.com/](https://api.stackexchange.com/)

**Base URL:** [https://api.stackexchange.com/2.3](https://api.stackexchange.com/2.3)

#### Properties

- [Documentation](https://api.stackexchange.com/docs)
- [Terms of Service](https://stackexchange.com/legal/api-terms-of-use)
- [Rate Limits](https://api.stackexchange.com/docs/throttle)
- [Sign Up](http://stackapps.com/apps/oauth/register)
- [OpenAPI](openapi/stack-overflow-openapi.yml)

### Stack Overflow for Teams API v3

The Stack Overflow for Teams API v3 provides read and write access to private team knowledge bases. It supports managing questions, answers, articles, user groups, subject matter experts (SMEs), and tags. Authentication uses Personal Access Tokens (PAT) via the Authorization Bearer header.

**Human URL:** [https://api.stackoverflowteams.com/docs](https://api.stackoverflowteams.com/docs)

**Base URL:** [https://api.stackoverflowteams.com/v3](https://api.stackoverflowteams.com/v3)

#### Properties

- [Documentation](https://api.stackoverflowteams.com/docs)
- [Blog](https://stackoverflow.blog/2023/05/17/stack-overflow-for-teams-api-v3/)
- [OpenAPI](openapi/stack-overflow-for-teams-openapi.yml)

## Common Properties

- [Website](https://stackoverflow.com)
- [Blog](https://stackoverflow.blog/)
- [Authentication](https://api.stackexchange.com/docs/authentication)
- [Sign Up](http://stackapps.com/apps/oauth/register)
- [Terms of Service](https://stackexchange.com/legal/api-terms-of-use)
- [JSON-LD](json-ld/stack-overflow-context.jsonld)
- [JSON Schema](json-schema/stack-overflow-question-schema.json)
- [Vocabulary](vocabulary/stack-overflow-vocabulary.yml)
- [Spectral Rules](rules/stack-overflow-rules.yml)

## Capabilities

### Shared Definitions (`capabilities/shared/`)

| File | Description |
|------|-------------|
| [stack-overflow-api.yaml](capabilities/shared/stack-overflow-api.yaml) | Stack Overflow public API — questions, search, similar questions, tags, and users (5 operations) |
| [stack-overflow-teams-api.yaml](capabilities/shared/stack-overflow-teams-api.yaml) | Stack Overflow for Teams API — team questions, articles, users, tags, and CRUD operations (6 operations) |

### Workflow Capabilities

| File | Description |
|------|-------------|
| [developer-knowledge-management.yaml](capabilities/developer-knowledge-management.yaml) | Developer Knowledge Management — unified workflow combining public Stack Overflow search with Teams knowledge base management (8 REST paths, 9 MCP tools) |
