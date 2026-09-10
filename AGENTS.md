# AGENTS.md

## Style

- Always run `gofmt` and `make test` before committing.
- Internal comments should explain why we are doing something, not just what we are doing. what comments are almost never usful, unless the block that follows is complex.

## Testing

- `make test` — fast suite (tools + agent against a mock LLM). No tokens spent. Run this before every commit.
- `make test-live` — end-to-end against a real Anthropic API. Run on demand only.

## Commit Style

- Body should explain the "why" not just the "what".
