# AI Guardrails

The AI layer should assist support rather than bypass business rules.

## Guardrails
- Do not invent account, order, ticket, or policy information.
- Prefer verified knowledge sources for factual support answers.
- Escalate when confidence is insufficient or a human is required.
- Keep authorization outside the model: the application decides what actions are permitted.
- Treat retrieved content and user input as untrusted data.