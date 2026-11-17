---
name: code-repair-coach
description: Review AI-generated code for known failure patterns, diagnose changes and verify candidate repairs.
---

# Unloopr

Use only the authorized `unloopr` MCP endpoint, at https://mcp.unloopr.com/mcp.

Read the original code or diff before suggesting a change. Retrieve known failed-fix history and compare an actual failing baseline. Flag unsupported packages or secret-shaped literals, distinguish warnings from verified defects, and verify the changed code by testing. Free scans are limited and paid checkout is not verified live. Never claim that Unloopr edits files or deploys automatically.

## Safe starter tasks
- Review this diff for hallucinated imports
- Find similar previous failed-fix patterns for this code
- Which originally reported findings still remain after the new diff?

## Acceptance

Verify tool discovery, normal owner consent and a real read in the target AI host. No output is a license to bypass service permissions. Stop on missing grant, unsupported tool, or stale evidence and explain what is needed next.
