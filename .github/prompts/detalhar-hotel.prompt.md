---
agent: agent
tools: ['runCommands', 'edit', 'search', 'perplexity/*', 'todos', 'fetch']
---
Based on requirements, fill in the details about the hotel provided.

Ask for the hotel if not provided.

## Instructions

- All requirements are detailed in: [Hoteis.md](../Hoteis.md#requisitos)
- Use #perplexity_search to find recent sources about the hotel
- Use #fetch to get full content from the sources
- If any requirement is not found, respond with "Information not available"
- Always check if all requirements are fulfilled before finishing
