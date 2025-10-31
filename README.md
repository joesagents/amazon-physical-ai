# [CASE NAME]

**Case Type:** Archival | Decision
**Topics:** [Topic 1], [Topic 2], [Topic 3]
**Difficulty:** [2, 2, 2] (Analytical, Ethical, Quantitative)
**Class Time:** 120 minutes
**Status:** Draft | Review | Submission-Ready

## Overview

[2-3 sentence case synopsis]

## Case Questions

1. [Question 1]
2. [Question 2]
3. [Question 3]

## Files

- `writing/draft.md` — Case narrative (~5,000-7,000 words)
- `exhibits/` — Visual materials (timelines, frameworks, data tables)
- `class/board-pack.md` — Instructor board plan (3-column layout)
- `teaching-note/teaching-note.md` — Instructor guide (learning objectives, discussion plan, rubrics)

## Usage

```bash
# Install CLI tool
pip install jittc-skill

# Validate case
jittc validate --stage $(jq -r .stage state.json)

# Run linters
jittc lint voice
jittc lint signposting

# Package for submission
jittc package
```

## License

- **Case Content:** CC BY-NC 4.0 (or your chosen license)
- **Teaching Notes:** Private (not distributed with case)

---

**Generated from:** [leenders-case-template](https://github.com/joesagents/leenders-case-template)
