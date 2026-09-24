# n8n Portfolio

Workflow automations and AI agents I've built with [n8n](https://n8n.io/) while learning automation engineering.

Each folder contains the exported workflow JSON, a README explaining how it works, and setup instructions.

## Projects

| # | Project | What it does | Tech |
|---|---|---|---|
| 01 | [AI Cybersecurity Briefing](01-ai-cybersecurity-briefing/) | Daily email of the latest security news, summarized and severity-rated by AI, critical threats first | RSS · Gemini · JavaScript · SMTP |
| 02 | [AI Resume Reviewer](02-ai-resume-reviewer/) | Web form where anyone uploads a resume PDF and receives an AI score, fixes, missing keywords and a rewritten summary by email | n8n Forms · PDF extraction · Gemini · JavaScript · SMTP |

## Using these workflows

1. In n8n, open the **⋯** menu and choose **Import from File**.
2. Select the project's `workflow.json`.
3. Add your own credentials (none are included in this repository).
4. Follow the setup steps in the project's README.

---

**Manya Monga** · [LinkedIn](https://www.linkedin.com/in/manya-monga-39ab1a374)
