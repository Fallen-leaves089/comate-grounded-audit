# Changelog

## 0.1.0 - 2026-11-19

- Split `comate-grounded-audit` from the grounded-audit lineage.
- Specialize the skill for Baidu Comate / `comatecli`, `~/.comate/skills`, `.comate/skills`, `.comate/rules/*.mdr`, `.comate/mcp.json`, hooks, plugins, `--activate-skill`, `Ask` / `Plan` / `Agent` modes, `requires_action`, background timeouts, and external memory.
- Add an ERNIE / routed-model risk-and-compensation profile for model identity drift, auto-approval misuse, suspended-action false completion, long-context summary drift, multimodal overclaim, malformed tool calls, and audit-to-architecture drift without claiming validated model behavior.
- Keep the default read-only contract, evidence-first P0-P3 reporting, fail-closed behavior, and append-only external memory.
