# Contract Reviewer — managed agent template

Reviews contracts for risk clauses, redlines issues, and generates amendment suggestions with a structured review report.

## What it does

1. Reads uploaded contract documents
2. Classifies sections (indemnification, liability, termination, IP, confidentiality, etc.)
3. Flags high-risk clauses with severity levels
4. Suggests alternative language for flagged clauses
5. Produces a structured review report as a Word document

## Skills

- **contract-analysis** — clause classification and risk assessment
- **docx-generation** — Word document output

## Usage

Deploy from the AgentStep catalog UI, or use the manifest directly:

```bash
claude agent start --manifest agents/contract-reviewer/agent.yaml
```
