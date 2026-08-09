# Demo Instructions - Copilot Energy GCC - Excel

Classification: Public

This demo uses a fictional Microsoft Fake Company created for demonstration purposes. Any resemblance to real organizations, people, products, services, or data is coincidental. Do not use customer confidential information in this repository.

## AI transparency declaration

This demo package includes AI-assisted and AI-generated fictional sample content created for demonstration purposes. See [AI-CONTENT-DECLARATION.md](AI-CONTENT-DECLARATION.md).

## Demo objective

Deliver a full 60-minute, industry-specific Microsoft 365 Copilot demo for **Excel** using fictional Contoso Energy Services work artifacts: Word brief, Excel readiness workbook, and PowerPoint executive briefing.

## Target audience

Cross-functional salaried employees in an energy/public-sector-adjacent organization, including operations, engineering, IT, finance, compliance, grants, HR, and communications stakeholders.

## Required artifacts for this demo

- [Word source brief](artifacts/work-documents/excel-industry-brief.docx)
- [Excel readiness workbook](artifacts/work-documents/excel-readiness-workbook.xlsx)
- [PowerPoint executive briefing](artifacts/work-documents/excel-executive-briefing.pptx)
- [Prompt library](prompts/excel-prompts.md)
- [Delivery folder](4018-excel/README.md)

## Environment assumptions and GCC limitation

Do not demonstrate live Copilot in a GCC tenant if Copilot is unavailable. Use these artifacts and the presenter-provided PPTX to narrate what the Copilot-enabled commercial tenant experience would look like. Do not show features learners do not have. This demo does not require web grounding, agents, researcher-style agents, YouTube, or external data.

## 60-minute run of show

| Time | Segment | Presenter action | Artifact |
|---:|---|---|---|
| 0-5 | Set context | Explain fictional scenario, Public classification, and GCC limitation. | Presenter PPTX |
| 5-12 | Work artifact tour | Open the Word, Excel, and PowerPoint sample documents and explain the business context. | Work documents |
| 12-22 | Prompting pattern | Show how to ask Copilot to summarize, transform, analyze, and critique work content. | Prompt library |
| 22-35 | Main Excel workflow | Walk through Analyze operational metrics, identify trends, and turn workbook insights into decisions. | App-specific artifact |
| 35-45 | Cross-app handoff | Explain how output from one app can become input for the next reviewed work product. | Word, Excel, PowerPoint |
| 45-52 | Human review | Identify what must be checked before sharing generated content. | Review checklist |
| 52-58 | GCC-safe fallback | Narrate the commercial Copilot experience without showing unavailable GCC features. | Presenter PPTX |
| 58-60 | Close | Summarize adoption guidance and Q&A handoff. | All artifacts |

## Demo script

1. State that all content is fictional and Public.
2. Open the Word source brief and identify the operational readiness problem.
3. Open the Excel workbook and point out risk scores, owners, workstreams, and suggested Copilot prompts.
4. Open the PowerPoint briefing and explain how it can be used as source material or an output target.
5. Use the prompt library to demonstrate or narrate the Excel workflow.
6. Call out that in GCC, Copilot may not be available; do not click into or imply unavailable functionality.
7. Explain expected outputs: summarized brief, risk prioritization, draft response, SOP, workbook insight, or executive slide narrative depending on the topic.
8. Close with a human-review checklist: facts, compliance, tone, missing context, sensitivity, and feature availability.

## Suggested talk track

"For this Excel demo, I am using fictional Contoso Energy Services work documents that resemble the kind of operational content an energy organization might already have in Microsoft 365. In a Copilot-enabled commercial tenant, I would ground the prompt in the open file or selected work content. In this GCC environment, if Copilot is not enabled, I will describe what the interaction would look like and avoid showing features that are not available."

## Expected outcomes

- Learners understand a complete 60-minute workflow, not a single prompt.
- The demo uses multiple realistic work artifacts, not one small CSV.
- The experience stays tenant-safe and avoids web grounding, agents, researcher-style capabilities, and YouTube.
- The presenter has enough artifacts to show app-specific and cross-app value.

## Cleanup

Remove any non-public presenter files after delivery. Keep this repository public-safe.
