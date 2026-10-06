# Telegram Beast Development Guide

## Architecture rule
Keep Telegram transport, AI reasoning, knowledge retrieval, ticketing, human escalation, and automation integrations separated by clear interfaces.

## Workflow
1. Change one domain at a time.
2. Keep credentials outside the repository.
3. Add tests for new business rules.
4. Validate webhook and bot error paths.
5. Document externally visible behavior.

## Commit standard
Prefer atomic messages such as `add ticket status transition validation` over vague messages like `update code`.
