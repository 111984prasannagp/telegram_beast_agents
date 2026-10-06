# Telegram Beast Testing Guide

## Test layers

### Unit tests
Cover intent routing, ticket state transitions, permission checks, prompt construction, and validation.

### Integration tests
Cover Telegram update handling, knowledge retrieval, persistence, and n8n boundaries using safe test credentials or mocks.

### Regression tests
Every production bug should gain a focused regression test when practical.

## Test data
Use synthetic customer information. Never commit real conversations, tokens, or private identifiers.
