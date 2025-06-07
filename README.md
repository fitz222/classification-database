# Human-Centric Algorithm Classification

This repository contains structured JSON data for evaluating algorithmic systems across eight developmental age stages.

## 📁 Structure

- `data/master.json` — Full flat list of all classifications
- `data/classifications/` — Individual JSON files per tool-age group

## 🧱 Naming Convention

Each file and entry uses the format:
`{tool_id}--{slugified-age-stage}.json`

## ➕ Adding New Entries

Each classification must include:
- tool_id, tool_name
- age_stage (one of 8 defined cohorts)
- scores for all 7 dimensions
- labels (if triggered)
- tags (optional)
- summary_guidance (3-sentence protocol)
- last_updated
