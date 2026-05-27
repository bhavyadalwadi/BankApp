# Primary App

## Responsibility
Main runtime for `BankApp`.

## Dependencies
- HTML
- CSS
- JavaScript
- Bootstrap
- jQuery

## Inbound APIs
- No formal inbound API is visible.

## Outbound APIs
- No confirmed external provider or downstream API.

## Databases Used
- No dedicated database visible.

## Queues / Topics
- No queue/topic layer visible.

## Critical Workflows
- Landing page with login form and carousel-based marketing content
- Enroll and forgot-password navigation
- Account-related static pages
- Shared navigation/footer partial loading through jQuery
- Mortgage-oriented content page

## Failure Modes
- Project maturity is uneven; expect weaker docs, less automation, and more manual assumptions than the active product repos.

## Scaling Concerns
- current implementation appears intentionally lightweight
- there is no evidence of multi-service scaling machinery unless repo docs add it

## Operational Concerns
- start from repo-local `.claude/` docs and Graphify summary before code changes
- validate environment assumptions before debugging logic

## Important Source Files
- `index.html`
- `account.html`
- `enroll.html`
- `forgot.html`
- `README.md`
- `README.MD`

## Dangerous Code Paths
- Project maturity is uneven; expect weaker docs, less automation, and more manual assumptions than the active product repos.

## Testing Strategy
- No standardized automated test command is visible.

## Known Technical Debt
- Pending work is unknown from current repo docs.
