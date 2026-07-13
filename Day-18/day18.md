# Day 18 — Building and Using a Custom Claude Skill

## Overview

Day 18 focused on creating and applying a **custom Claude Skill** — the `brain-dump-action-planner`. This skill transforms unstructured notes, meeting transcripts, and brainstorming sessions into clean, structured, and visually organized output. The goal was to explore how custom skills extend Claude's capabilities for real-world productivity workflows.

## Objective

- Understand how custom Skills are defined and structured for Claude.
- Build a skill that converts messy, unstructured notes into an organized, actionable format.
- Apply the skill to a real meeting-notes example and generate a polished, interactive output.
- Document the process, learnings, and output for future reference.

## About the Custom Skill

**Skill name:** `brain-dump-action-planner`

**Purpose:** Transform messy notes, meeting transcripts, voice memos, brainstorming sessions, and stream-of-consciousness thoughts into structured summaries, action plans, decisions, open questions, and task lists — without inventing, assuming, or filling gaps.

**Key design principles:**
- Preserve all names, dates, numbers, and terminology exactly as provided.
- Never infer or complete missing information — display `Not specified` instead.
- Support multiple modes, including a **Transcript Mode** for speaker-labeled notes and a **Merge Mode** for combining multiple sources.
- Output is generated as a self-contained, interactive HTML artifact styled like a modern project dashboard (Notion / Linear / Asana-inspired).

## Steps Followed

1. **Defined the skill** — Created a `SKILL.md` file specifying the skill's name, description, output requirements, and formatting rules.
2. **Specified required sections** — Summary, Key Takeaways, Action Items, Open Questions, Risks/Blockers, Conflicts, and Additional Notes.
3. **Added status badges** — Standardized indicators (High/Medium/Low priority, Conflict, Open Question, Completed, Pending) for visual clarity.
4. **Enabled Transcript Mode** — Added support for speaker-labeled notes, including speaker summaries, decisions by speaker, and action items by speaker.
5. **Tested the skill** — Ran a sample project meeting transcript through the skill.
6. **Generated the output** — Produced a fully interactive HTML dashboard summarizing the meeting.
7. **Reviewed accuracy** — Verified that no information was invented and that missing details were correctly marked as `Not specified`.

## Features

- 📋 Automatic extraction of **action items** with task, owner, deadline, and status.
- 🗣️ **Speaker-aware parsing** for transcript-style notes.
- ⚠️ Dedicated **Conflicts** section to flag inconsistent deadlines, owners, or decisions.
- ❓ Clear separation of **Open Questions** from resolved decisions.
- 🎨 Clean, responsive **dashboard-style UI** with cards, badges, and collapsible sections.
- 🚫 Strict **no-hallucination policy** — missing data is never guessed or filled in.

## Screenshots

> _Add screenshots of the generated HTML dashboard here, for example:_
>
> - `screenshots/day18-summary-view.png`
> - `screenshots/day18-action-items-table.png`
> - `screenshots/day18-speaker-breakdown.png`

## Key Learnings

- Custom Skills allow Claude to consistently follow a defined output structure across different types of input.
- Explicit rules (like "never invent missing information") are essential for building trustworthy, reusable automation.
- Transcript-style inputs benefit from speaker-level attribution to avoid misassigning tasks or decisions.
- A well-designed skill can turn a single block of raw text into a decision-ready, presentation-quality artifact in one pass.

## Files Included

| File | Description |
|------|--------------|
| `SKILL.md` | Definition of the custom `brain-dump-action-planner` skill |
| `meeting_breakdown.html` | Sample structured output generated from a project meeting transcript |
| `day18.md` | This documentation file summarizing Day 18's work |

## Conclusion

Day 18 demonstrated how a custom Claude Skill can standardize the way unstructured information — like meeting notes — is turned into organized, actionable output. By enforcing strict formatting and accuracy rules, the `brain-dump-action-planner` skill produces reliable, presentation-ready dashboards without fabricating details. This exercise highlighted the value of well-scoped, rule-driven skills for building repeatable productivity workflows with Claude.
