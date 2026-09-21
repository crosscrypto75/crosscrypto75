# Jérémy — Agentic AI & AI Systems

I build AI systems around a simple principle:

> AI should be powerful where reasoning is useful, deterministic where rules are sufficient, and bounded where mistakes can create real consequences.

## Current focus

- Agentic AI architectures
- Provider-agnostic orchestration
- Multi-agent Builder / Validator workflows
- Capability and permission boundaries
- Context routing and memory control
- Durable execution and failure recovery
- AI integration into existing business software
- Decision systems and autonomous experimentation

## Selected work

### Universal Agent Harness — private

Provider- and domain-agnostic infrastructure for bounded agent execution. Current work includes a deterministic task lifecycle, policy and capability enforcement, Builder / Corrector / Validator workflows, provider routing, supervised Claude and Codex workers, durable execution and recovery, reconciliation, context routing and budgeting, controlled memory retrieval, SQLite and in-memory persistence, and deterministic test coverage.

The implementation remains private. A public technical showcase will focus on architecture and demonstrations without exposing proprietary internals.

### Investment Brain — private

An experimental market-intelligence and decision-system platform using structured data, risk management, simulation/paper trading, and AI-assisted analysis. Its proprietary decision rules, trading signals, thresholds, and scoring logic are not published.

### Local-first Accounting Application — private

A real business application built around a practical division of responsibility:

- AI for document understanding
- Deterministic rules for reconciliation
- Human validation when confidence is insufficient

Private business data and implementation details remain private.

### Multichain / Solana Experiment — in development

An in-development exploration of bridge routing, route-risk evaluation, account abstraction, cross-chain execution, and failure/fallback handling. It is not presented as a finished product.

## Engineering principles

- Evidence > opinion
- Deterministic when possible, probabilistic when useful
- Requested capability != granted authority
- Validation should be independent from generation
- Unknown external outcome != permission to retry blindly
- Applications should not depend on a single AI provider
- AI infrastructure should plug into products, not force products to be rebuilt around it

## Tech

TypeScript, Node.js, SQLite, Python, Git, and LLM APIs/CLIs.