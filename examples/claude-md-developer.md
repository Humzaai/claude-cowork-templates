# CLAUDE.md — Developer Example

> This is a fully filled-in example for a software developer or engineer.
> Copy it, rename to CLAUDE.md, replace every detail with your own information, and save it to your workspace root.

---

## WHO I AM

I am Sam Park, a senior backend engineer at a Series B fintech company. I work primarily in Python and Go, building the data pipeline and API infrastructure. My goal is to lead the migration of our monolith to a service-oriented architecture by Q4 2026, and to complete my AWS Solutions Architect certification by September 2026.

---

## MY WORK

- Main deliverables I produce: Code (Python, Go), architecture decision records (ADRs), API documentation, technical specs, PR reviews, runbooks, post-mortems
- Tools I use daily: VS Code, GitHub, Docker, Kubernetes, AWS (ECS, RDS, S3, Lambda), Datadog, Notion, Slack, Linear
- Industries I work in: Fintech, payments infrastructure
- Clients or audience I serve: Internal engineering team (8 engineers), product managers, and occasionally the CTO during architecture reviews
- Current active projects: Monolith-to-SOA migration (Phase 1: auth service extraction), AWS certification study, improving observability in the data pipeline

---

## MY VOICE AND TONE

- Writing style: Precise and concise. In documentation, I write for a mid-level engineer who is smart but unfamiliar with this specific system — not for experts, not for beginners.
- Words I always use: "trade-off," "constraint," "observable," "idempotent," "failure mode"
- Words I never use: "self-explanatory," "simply," "just" (makes hard things sound easy), "best practice" without specifying which practice and why
- Format preference: Code blocks for all code snippets, numbered steps for runbooks, headers for long docs, short paragraphs
- Emoji use: None in technical documents or PRs. Fine in Slack.

---

## MY GOALS RIGHT NOW

1. Complete auth service extraction from monolith and deploy to staging by August 31, 2026
2. Pass AWS Solutions Architect (Associate) exam by September 15, 2026
3. Write and publish 3 internal ADRs documenting architecture decisions from Q2 so they don't get lost

---

## BEFORE YOU WRITE ANYTHING, READ THESE FILES

- For code documentation: Read `templates/12-code-documentation.md`
- For workflow SOPs and runbooks: Read `templates/10-workflow-sops.md`
- For research (architecture options, tool comparisons): Read `templates/03-research-framework.md`
- For experiment tracking (testing new tools or approaches): Read `templates/25-ai-experiment-log.md`
- For data analysis tasks: Read `templates/11-data-analysis.md`

---

## MY RULES

- Always include the "why" in code comments, not the "what" — the code shows what, the comment explains why this approach was chosen over alternatives
- Always specify the exact version when referencing a library, tool, or service — never "use Redis," always "use Redis 7.2 with AOF persistence enabled"
- Never give a code example that would fail in a production environment due to missing error handling or hardcoded credentials
- Never recommend a tool without naming at least one trade-off — everything has a cost
- When I paste an error message: identify (1) what caused it, (2) what it means in plain English, (3) the fix, (4) how to prevent it next time
- Default ADR format: Context → Decision → Alternatives considered (and why rejected) → Consequences → Status

---

## ADDITIONAL CONTEXT

Our stack: Python 3.11, Go 1.22, PostgreSQL 15, Redis 7, Kafka 3.6, Kubernetes 1.29 on AWS ECS. We use trunk-based development with feature flags. Our service SLA is 99.9%. We do not use ORMs — all SQL is written directly. When suggesting database patterns, account for this.

---

## MY SIGN-OFF

No sign-off on internal docs. For external documentation or README files: "Maintained by the Platform Team."
