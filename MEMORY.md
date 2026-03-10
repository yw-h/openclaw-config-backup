# MEMORY.md - Long-term memories

## Work Preferences & Rules

### Tool Usage Priority
- **MCP tools first**: For web searches and external data, always prefer using configured MCP servers (via mcporter) over direct curl/API calls.
  - Examples: weibo.get_trendings, exa.web_search_exa
  - Benefits: Better reliability, standardized interfaces, and proper tool documentation

### Internet Operations
- **Agent-reach for internet**: All internet-related operations (web searches, reading online content, social media data) must be performed using the `agent-reach` tool via MCP, never through direct curl or raw API calls.
  - This ensures consistent tool interfaces and proper error handling.

### General Principles
- Be resourceful before asking questions
- Maintain concise, helpful communication
- Use Chinese as the primary language when interacting with Sir Yiwei

---

*Last updated: 2026-03-10 (added internet ops rule)*