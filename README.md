<div align="center">

# 👋 Wrong link, sorry!

**You are looking for [`abdessalllam/agent-safeguards`](https://github.com/abdessalllam/agent-safeguards)** (with an **s** at the end).

This repository is only a signpost. I mistyped the name in a link I shared, and this page is here so nobody ends up on a dead end. It holds no code.

### ➡️ [github.com/abdessalllam/agent-safeguards](https://github.com/abdessalllam/agent-safeguards)

</div>

---

## What you were looking for

**Agent Safeguards** is a plugin for Claude Code and Codex that adds shell-command guardrails:

- **safe-tool** keeps identity and credential data out of the transcript. It blocks commands that print it and withholds output that contains it.
- **delete-guard** stops deletes that could wipe a drive. It blocks recursive deletes outside the current repository and temp folders.

Everything runs locally: Python standard library only, no network, no telemetry, no account.

## Install

Use the name with the **s**:

```sh
# Claude Code
claude plugin marketplace add abdessalllam/agent-safeguards
claude plugin install agent-safeguards@abdessalllam

# Codex
codex plugin marketplace add abdessalllam/agent-safeguards
codex plugin add agent-safeguards@abdessalllam
```

The [real repository](https://github.com/abdessalllam/agent-safeguards) has the full README, the settings, and the security policy.
