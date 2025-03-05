---
name: Bug report
about: Report an issue with the mcp-sentry tool
title: "[BUG] "
labels: bug
assignees: qianniuspace

---

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Command or configuration used (e.g. command line arguments, config file settings)
2. Authentication method used (e.g. environment variables, config file)
3. Sentry configuration details:
   - Project slug
   - Organization slug
   - API access level
4. Error message or unexpected output

**Expected behavior**
A clear and concise description of what you expected to happen.

**Actual behavior**
What actually happened, including:
- Full error message/stack trace
- Relevant logs (please remove sensitive information)
- Response data if available
- Any error codes received

**Environment information:**
 - OS: [e.g. macOS 13.1, Windows 11, Ubuntu 22.04]
 - Python version: [e.g. 3.10.5]
 - mcp-sentry version: [e.g. 0.6.2]
 - Installation method: [e.g. pip, uv, docker]
 - Integration client: [e.g. Claude Desktop, Zed, Cursor]
 - Client version: [specify version]

**Configuration files**
Please include relevant parts of your configuration files (with sensitive information removed):
```json
// claude_desktop_config.json or settings.json
{
  // Your configuration here
}
```

**Dependency versions:**
- mcp: [e.g. 1.0.0]
- httpx: [version]
- click: [version]

**Additional context**
- Were you accessing a specific Sentry issue or listing issues?
- Did the issue occur after any recent changes to your environment?
- Is this reproducible in other environments?
- Any relevant Sentry API response details?

**Debugging attempts**
- Have you tried using the MCP inspector? If yes, what were the results?
- Have you checked the Sentry API access in other tools?
- Any relevant debugging logs or inspector output?

**Screenshots**
If applicable, add screenshots to help explain your problem. Please ensure no sensitive information is visible.
