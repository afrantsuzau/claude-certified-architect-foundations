# Claude Certified Architect — Foundations: Exam Prep

Hands-on notebooks and exercises for preparing for Anthropic's **Claude Certified Architect – Foundations** certification. The exam checks that you can design, scope, and build production-ready applications with Claude.

## Exam at a glance

- 60 scenario-based questions; each exam randomly draws 4 of 6 scenarios
- Passing score: 720 / 1000

## Exam domains

| Domain | Weight | Key topics |
|---|---|---|
| **Agentic Architecture & Orchestration** | 27% | Agent loops, multi-agent / subagent patterns, workflows vs. agents, task decomposition, human-in-the-loop, failure handling |
| **Claude Code Configuration** | 20% | `CLAUDE.md`, settings & permissions, hooks, slash commands, skills, subagents, CI / headless usage |
| **Prompt Engineering** | 20% | System prompts, clear instructions, examples (few-shot), XML structuring, structured output, prompt evaluation |
| **Tool Design & MCP** | 18% | Tool schemas and descriptions, tool-use loop, error handling, MCP servers / clients, resources & prompts |
| **Context Management & Reliability** | 15% | Context window limits, prompt caching, retrieval / RAG, summarization and compaction, evals, guardrails |

The weights come from third-party study guides that quote Anthropic's exam guide. Check them against the official exam guide.

## Setup

```bash
python -m venv .venv && source .venv/bin/activate
pip install anthropic python-dotenv jupyter
echo "ANTHROPIC_API_KEY=sk-ant-..." > .env
```
