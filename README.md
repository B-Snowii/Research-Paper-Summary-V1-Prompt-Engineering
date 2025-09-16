[![Language](https://img.shields.io/badge/Language-English-blue)](README.md)
[![语言](https://img.shields.io/badge/语言-中文-red)](README.zh-CN.md)

# Academic Paper Summary · V1 Prompt Engineering

This repository showcases a workflow and key implementation for generating professional around 25-word summaries for academic papers, built for a research institute.

- Task: Produce around 25-word academic summaries for many papers weekly, used in weekly Research alerts.
- Key Outcomes:
  - Time cost: Before over 40 hrs/week → After ≤ 2 hrs/week
  - Quality assurance: Method/topic accuracy and consistent style
  - Reusability: MCP pipeline + edits data
- Background & Goals:
  - Time constraint: Summaries finalized within 4 days due to time sensitivity.
- Practical Challenges:
  - High volume and urgency
  - Broad topics and methods; high comprehension cost
  - Repeated internal edits and communication

## Version Rationale (V1 · Prompt Engineering)
- Why this attempt: Zero‑infra fast iteration; meet strict length/method/tone constraints via prompt design.
- Why we moved on: Despite extensive prompt/shot tuning (GPT‑4.1, DS‑V3/DS‑R1, NotebookLM, Flan‑T5, T5‑Large), outputs skewed to general readership; academic tone and method precision inconsistent.

## Links
- Main repo: https://github.com/B-Snowii/Research-Paper-Summary-Collection
- License: MIT
