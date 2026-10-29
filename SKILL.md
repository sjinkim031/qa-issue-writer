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

## Output format

### 이슈 제목
[기능명] 문제 현상을 간결하게 요약

### 재현 절차
1. 확인된 조작 순서
2. 문제가 발생하는 조건

### 오류 상황
문제가 발생한 화면 또는 조건.

### 오류 내용
실제로 관찰된 동작이나 표시.

### 기대 결과
기획서, 명세서 또는 사용자 요구사항에 근거한 정상 동작. 근거가 없으면 `확인 필요`로 표기.

## Writing rules

- Use neutral, concise Korean appropriate for a defect tracker.
- Describe what happens, not why it happens, unless the cause is verified.
- Preserve exact UI labels, error messages, and numeric limits.
- Avoid duplicated information across sections.
- Do not claim a defect is reproducible unless reproduction was confirmed.
- If the user requests only a title, output only the title.



