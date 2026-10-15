# AI Productivity Toolkit — Prompt Engineering & AI Productivity

A reusable, beginner-friendly collection of prompt templates and practice workflows for summarization, classification, structured JSON output, content generation, resume/email writing, coding help, debugging, and research assistance.

## Project goals

- Practice **zero-shot** and **few-shot** prompting.
- Make prompts clearer using **role, context, instructions, constraints, and output format**.
- Request structured responses such as valid JSON.
- Reuse prompts for summarization, classification, generation, email, resumes, coding, debugging, and research.
- Evaluate prompts using a repeatable test report instead of judging only one response.

## Repository structure

```text
ai-productivity-toolkit/
├── README.md
├── prompts/
│   └── prompt_templates.md
├── src/
│   └── toolkit.py
├── tests/
│   └── test_toolkit.py
├── reports/
│   └── prompt_evaluation_report.md
└── AI_Productivity_Toolkit_Colab.ipynb
```

## Quick start

This project uses only the Python standard library for its core prompt-building functions.

1. Download or clone this repository.
2. Open `AI_Productivity_Toolkit_Colab.ipynb` in [Google Colab](https://colab.research.google.com/).
3. Run the notebook cells from top to bottom.
4. Copy a generated prompt into an AI assistant, inspect the response, and record the result in `reports/prompt_evaluation_report.md`.
5. Edit the examples with your own inputs before submission.

To run the tests locally from the repository root:

```bash
python -m unittest discover -s tests -v
```

## Prompt design pattern

A useful reusable prompt usually specifies:

1. **Role** — which perspective the AI should take.
2. **Context** — background and the target audience.
3. **Task/instructions** — the action to perform.
4. **Constraints** — length, tone, exclusions, and accuracy requirements.
5. **Output format** — bullets, table, JSON, code, or another defined structure.
6. **Examples** — optional demonstrations for few-shot prompting.

## Example workflows

- **Summarization:** turn a long passage into a short summary and key points.
- **Classification:** classify feedback as `positive`, `neutral`, or `negative` and return JSON.
- **Generation:** draft a professional email, resume bullet, or LinkedIn post.
- **Coding/debugging:** ask for the root cause, a minimal fix, and a test case.
- **Research assistance:** request a structured research plan, source checks, and a clear distinction between facts and assumptions.

## Zero-shot vs. few-shot

- **Zero-shot:** give instructions without examples.
- **Few-shot:** include a small number of input/output examples to show the desired pattern.

The notebook contains examples of both approaches and a small prompt-quality evaluation exercise.

## Responsible use

AI output may be incorrect or incomplete. Verify important claims, run and test generated code, avoid entering passwords or private data, and check facts against trustworthy sources. Do not present generated or illustrative examples as verified research.

## Submission checklist

- [ ] Push this folder to your GitHub account.
- [ ] Upload `AI_Productivity_Toolkit_Colab.ipynb` to Google Colab and save a copy to your Drive.
- [ ] Replace the placeholders in your LinkedIn post with your actual repository and notebook links.
- [ ] Run the notebook and update the evaluation report with your own results.
