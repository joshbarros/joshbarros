# Josué Barros

## Backend and integration engineering for existing software products

I implement backend features, connect APIs and improve reliability. Work directly with me through a written scope, your issue tracker and reviewed pull requests.

**[Discuss an engineering task →](https://josuebarros.com/services#project-brief)** · [Experience](https://josuebarros.com/about) · [LinkedIn](https://linkedin.com/in/joshbarros) · [Email](mailto:hello@josuebarros.com)

## Start with the engineering evidence

These are public reference projects, not client case studies. They show implementation choices and tests you can inspect. They are not claims of production deployments, customer results or guaranteed reliability.

### Reliable workflows and inventory — .NET / PostgreSQL / messaging

**[dotnet-warehouse](https://github.com/joshbarros/dotnet-warehouse)** demonstrates order processing with transaction boundaries, an outbox/inbox, retries and compensating actions.

- **Buyer concern:** two orders compete for the last unit, or a message arrives twice.
- **Inspect:** [concurrency and duplicate-delivery tests](https://github.com/joshbarros/dotnet-warehouse/blob/main/tests/Warehouse.IntegrationTests/InventoryConcurrencyTests.cs), [outbox relay](https://github.com/joshbarros/dotnet-warehouse/blob/main/libs/shared/Messaging/OutboxRelay.cs), and [architecture and local demo](https://github.com/joshbarros/dotnet-warehouse#readme).
- **Verification:** [CI runs](https://github.com/joshbarros/dotnet-warehouse/actions/workflows/ci.yml), including database integration and browser test jobs. Check the relevant run and commit for its current status.

### Document AI with inspectable safeguards — Python / FastAPI

**[production-rag](https://github.com/joshbarros/production-rag)** explores document retrieval, citation validation, refusal behavior and usage budgets.

- **Buyer concern:** an AI feature returns unsupported answers or consumes more budget than expected.
- **Inspect:** [citation and refusal tests](https://github.com/joshbarros/production-rag/blob/main/packages/core/tests/test_grounding.py), [budget tests](https://github.com/joshbarros/production-rag/blob/main/packages/core/tests/test_phase6_budget.py), and [evaluation artifacts](https://github.com/joshbarros/production-rag/tree/main/packages/core/evals/results).
- **Verification:** [CI runs](https://github.com/joshbarros/production-rag/actions/workflows/ci.yml) and reproducible evaluation commands. Citation checks reduce a class of failures; they do not guarantee that every answer is correct.

## How we work together

1. **Send a short brief.** The task, expected behavior, current stack and deadline are enough to start. Please omit credentials and confidential customer data.
2. **Agree on a paid implementation trial.** We define scope, acceptance criteria, price and timing in writing before work begins.
3. **Review the work.** You receive code, tests and a written handover in your tools. Ongoing monthly engineering is available when the backlog and working relationship fit.

No introductory sales call is required. Any useful technical meeting is arranged in advance. [See the current engagement terms and capacity →](https://josuebarros.com/services)

## Engineering approach

I use CLI tools and coding agents to accelerate implementation. I remain responsible for reviewing changes, testing behavior, explaining tradeoffs and handing over maintainable work. Tools are part of the process; the deliverable is working software you can inspect and own.

My background spans backend, data and full-stack engineering. [Career history and experience →](https://josuebarros.com/about)

## Technical writing

- [The N+1 query problem, measured](https://josuebarros.com/blog/n-plus-1-query-problem-measured)
- [Terraform mistakes senior engineers make](https://josuebarros.com/blog/terraform-mistakes-senior-engineers-make)
- [From vague instructions to specifications](https://josuebarros.com/blog/github-spec-kit-stop-vibe-coding)

[More writing](https://josuebarros.com) · [YouTube](https://youtube.com/@theitguyreturns)
