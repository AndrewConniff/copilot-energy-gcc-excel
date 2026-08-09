# Demo Instructions - Copilot Energy GCC - Excel

Classification: Public

This demo uses a fictional Microsoft Fake Company created for demonstration purposes. Any resemblance to real organizations, people, products, services, or data is coincidental. Do not use customer confidential information in this repository.

## AI transparency declaration

This demo package includes AI-assisted sample content created for demonstration purposes. See [AI-CONTENT-DECLARATION.md](AI-CONTENT-DECLARATION.md).

## Demo objective

Help learners understand practical Microsoft 365 Copilot value for **Excel** using a fictional Contoso Energy Services scenario while respecting GCC limitations and the delivery document constraints.

## Target audience

Cross-functional salaried employees, including operations, engineering, IT, finance, and HR stakeholders.

## Persona setup

- **Presenter:** Microsoft trainer delivering a private virtual session.
- **Fictional user:** Jordan Lee, Operations Program Manager at Contoso Energy Services.
- **Fictional business context:** Jordan coordinates operational updates, internal communications, and executive-ready summaries across energy program teams.

## Prerequisites and environment assumptions

- Presenter-supplied PPTX is available separately.
- Demo does not require agents, researcher-style capabilities, web grounding, YouTube, or live external data.
- GCC tenant may not have Microsoft 365 Copilot available. If Copilot is unavailable, narrate the experience and use the included prompts, sample data, and PPTX rather than attempting a live Copilot demo.

## Timing guidance

| Segment | Time | Activity |
|---|---:|---|
| Set context | 5 min | Explain fictional scenario, Public classification, and GCC limitation |
| Concept walkthrough | 10 min | Show where Excel Copilot would appear in a Copilot-enabled tenant |
| Prompt walkthrough | 20 min | Use prompts/excel-prompts.md and sample data to explain expected results |
| Adoption guidance | 10 min | Discuss safe prompting, review, and validation habits |
| Q&A | 5 min | Redirect unsupported platform or agent questions back to Copilot scope |

## Step-by-step demo script

1. Open the presenter-supplied PPTX and state: "This demo uses fictional Contoso Energy Services content and is designed to avoid web grounding, agents, and external data."
2. Remind the audience: "In this GCC environment, Copilot may not be available. I will call out what this would look like in a Copilot-enabled tenant and avoid showing features that are not enabled here."
3. Introduce the Excel scenario: Analyze fictional production and support-function data, summarize trends, and generate insights.
4. Open sample-data/production-data.csv or the matching notes in the PPTX.
5. Read the primary prompt from prompts/excel-prompts.md.
6. Explain the expected Copilot behavior in a commercial Copilot-enabled tenant:
   - Copilot grounds on the selected mailbox, document, workbook, or presentation content available to the signed-in user.
   - Copilot should produce a draft or summary that the user reviews before sharing.
   - Copilot does not replace business judgment or compliance review.
7. Show the expected outcome in the PPTX or narrate the result if no live Copilot is available.
8. Close by emphasizing that feature availability must be confirmed in the learner tenant.

## Suggested talk track

"For this Excel example, imagine Jordan at Contoso Energy Services has content already available in Microsoft 365. In a Copilot-enabled commercial tenant, Jordan would open the relevant Microsoft 365 app, select the content, and ask Copilot to help summarize, draft, analyze, or transform it. In this GCC tenant, we may not have Copilot enabled, so I am using a public-safe fictional scenario to show the workflow concept without exposing unavailable features."

## Primary prompt

`	ext
Analyze this worksheet, identify trends or anomalies, and suggest three questions I should ask the operations team.
`

## Expected outcomes and validation points

- Output is clearly based on the provided fictional content, not web results.
- Output includes useful structure, next steps, or insights appropriate to Excel.
- Presenter reminds learners to review, edit, and validate before using any generated content.
- Presenter does not imply GCC feature availability that has not been confirmed.

## Troubleshooting tips

- If Copilot is unavailable, use the PPTX and describe the expected interaction.
- If a learner asks about agents or researcher-style experiences, explain that they are out of scope for this delivery.
- If a prompt appears to need web content, revise it to use only the provided file, email, worksheet, document, or presentation content.

## Supporting files

- [Delivery run sheet](4018-excel/README.md)
- [Prompt library](prompts/excel-prompts.md)
- [Sample data](sample-data/production-data.csv)
- [PPTX drop instructions](artifacts/PPTX-DROP-INSTRUCTIONS.md)
- [Environment checklist](setup/environment-checklist.md)

## Cleanup

Remove any local copies of presenter-provided PPTX files if they contain non-public delivery materials. Keep this repository public-safe only.

## GitHub download links

- [Repository README](https://github.com/AndrewConniff/copilot-energy-gcc-excel/blob/main/README.md)
- [Manifest](https://github.com/AndrewConniff/copilot-energy-gcc-excel/blob/main/manifest.json)
- [AI content declaration](https://github.com/AndrewConniff/copilot-energy-gcc-excel/blob/main/AI-CONTENT-DECLARATION.md)
- [PPTX drop instructions](https://github.com/AndrewConniff/copilot-energy-gcc-excel/blob/main/artifacts/PPTX-DROP-INSTRUCTIONS.md)
- [Environment checklist](https://github.com/AndrewConniff/copilot-energy-gcc-excel/blob/main/setup/environment-checklist.md)

