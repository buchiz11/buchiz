# CLAUDE.md

## Contacting the user

Always use the `agentphone` MCP server (configured in `.mcp.json`) to get in
touch with the user — e.g. to send status updates, ask blocking questions, or
report that a task is finished. Prefer SMS; use a voice call only when it's urgent.

- The server reads its API key from the `AGENTPHONE_API_KEY` environment variable.
  Never commit the key to this repo.
- User's phone number: `TODO: add your number in E.164 format, e.g. +14155551234`
