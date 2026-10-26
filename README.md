# AI Prompt Evaluation & Testing Framework

A modular Python and Jupyter Notebook framework designed to systematically test, benchmark, and score LLM prompts using the Anthropic API (Claude Haiku)[cite: 1, 2, 3, 4]. 

This project acts as an automated evaluation pipeline that replaces manual prompt tweaking with objective, criteria-driven scoring and rich reporting.

---

## Key Features

* **Automated Dataset Generation:** Dynamically generates diverse test cases and scenarios based on your core task description and prompt input specifications.
* **LLM-as-a-Judge Evaluation:** Rigorously scores outputs against specific, measurable solution criteria and optional mandatory requirements[cite: 4].
* **Syntax & Structural Validation:** Supports programmatic checks (like JSON, Python AST, and Regex validation) alongside AI grading[cite: 1, 3].
* **HTML Report Generation:** Compiles evaluation results into a polished, single-command HTML visual report complete with summary statistics, score badges, and detailed reasoning[cite: 4].

---

## Project Structure

```text
├── 001_prompt_evals_fns.ipynb    # Core functional implementation notebook
├── 001_prompt_evals_grader.ipynb   # Interactive grading & testing notebook
├── 002_prompting_completed.ipynb # Full pipeline with HTML report generation
├── prompting.py                  # Standalone Python script version of the evaluator
├── dataset.json                  # Sample test dataset
├── datasetcheck.json             # Additional configuration test dataset
├── output.json                   # Structured JSON output from evaluations
└── output.html                   # Generated visual evaluation report
```
---

