---
name: qa-issue-writer
description: Convert rough software QA observations into clear, reproducible issue reports in Korean.
metadata:
  { "openclaw": { "emoji": "🧪" } }
---

# QA Issue Writer

## Purpose

Turn informal bug notes, screenshots described by the user, or test observations into concise, actionable QA issue reports. Do not invent reproduction steps, environment details, or expected behavior.

## When to use

- A user asks to summarize an error or defect.
- A user needs an issue title, reproduction steps, actual result, or expected result.
- A user wants an existing QA report rewritten more clearly.

## Workflow

1. Identify the affected feature, triggering action, and observed behavior.
2. Separate confirmed facts from assumptions or missing details.
3. Write a short issue title using the format `[Feature] Observable problem`.
4. Describe the actual result objectively.
5. State the expected result only if supported by the specification or user-provided requirements.
6. Add reproduction steps only when enough information is available.
7. If a critical detail is missing, mark it `확인 필요` rather than guessing.


