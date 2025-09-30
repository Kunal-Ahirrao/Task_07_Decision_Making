# Task_07_Decision_Making (Kunal) — FULL

Turn the Task 6 LLM interview (SU Women’s Lacrosse) into a stakeholder-facing decision report with **uncertainty**, **fairness**, **robustness**, and **full provenance**.

## Quickstart
```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
cp config/config.example.yaml config/config.yaml  # then edit paths/columns if needed
python scripts/run_pipeline.py
```

## Bring In Task 4 & Task 5 (optional but recommended)
- Drop Task 4 artifacts in `archives/task4/` and Task 5 artifacts in `archives/task5/`.
- Follow `INTEGRATION_GUIDE.md` to auto-reference prior prompts, outputs, and visuals in the report.
- We reference Task 5 descriptive stats as baseline and Task 6 interview as the LLM narrative.

## Outputs
- Final report: `results/report/stakeholder_report.md`
- Tables: `results/tables/`
- Figures: `results/figures/`

**Disclosure:** LLM-generated content is clearly labeled in the report.


## Added for Task 7 (per your rubric)
- `logs/llm_prompt_log.md` — full prompts, outputs, and edit annotations.
- `prompts/decision_prompt_template.txt` — decision prompt template.
- `scripts/analysis_descriptives.py`, `bootstrap_ci.py`, `fairness_checks.py` — standardized CLI tools.
- `reports/stakeholder_report_template.md` — lacrosse-adapted structure.
- `seeds.json` — canonical seeds used for runs.
- `outputs/` — mirrors `results/` for tables/figures referenced in the report.
