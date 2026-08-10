# Demo Instructions - Copilot Energy GCC - Excel

Classification: Public

This demo uses a fictional Microsoft Fake Company created for demonstration purposes. Any resemblance to real organizations, people, products, services, or data is coincidental. Do not use customer confidential information in this repository.

## How to use this document

This is the only runbook you need for the Excel demo. Each step tells you which file to open, the exact prompt to use when Copilot is available, what result to expect, and what to say when you cannot show Copilot in GCC. You do not need a separate prompt file.

## Demo objective

Demonstrate Copilot-style workbook analysis for fictional energy readiness metrics and operational risk review.

## Required files

- Word source brief: `artifacts/work-documents/excel-industry-brief.docx`
- Excel readiness workbook: `artifacts/work-documents/excel-readiness-workbook.xlsx`
- PowerPoint briefing deck: `artifacts/work-documents/excel-executive-briefing.pptx`

## GCC limitation

If Copilot is not available in the GCC tenant, do not click into or imply unavailable Copilot functionality. Use the included files and presenter PPTX to narrate what the Copilot-enabled commercial tenant experience would look like. Do not use web grounding, agents, researcher-style agents, YouTube, real customer data, or private tenant details.

## 60-minute run of show

| Time | Segment | What you do |
|---:|---|---|
| 0-5 | Set context | Explain fictional Contoso Energy Services scenario and GCC limitation. |
| 5-12 | Source file tour | Open the Word, Excel, and PowerPoint work documents. |
| 12-20 | Prompting pattern | Explain role, task, context, format, and review criteria. |
| 20-42 | Main demo workflow | Run or narrate the step-by-step prompts below. |
| 42-52 | Cross-app handoff | Show how output becomes a draft response, SOP, workbook insight, or slide outline. |
| 52-58 | Human review | Review accuracy, compliance, sensitivity, tone, and feature availability. |
| 58-60 | Close | Summarize adoption guidance and Q&A handoff. |

## Step-by-step demo with prompts

### Step 1: Set context

**Open this file:** `README.md and presenter PPTX`

**Prompt to use:**

```text
No prompt. Explain that the Excel workbook contains fictional readiness metrics for energy operations workstreams.
```

**Expected result:** Audience knows the workbook is safe, fictional, and public.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

### Step 2: Open the workbook

**Open this file:** `artifacts/work-documents/excel-readiness-workbook.xlsx`

**Prompt to use:**

```text
No prompt. Show the Readiness Metrics worksheet columns: workstream, facility, priority, open actions, risk score, owner, and Copilot use case.
```

**Expected result:** Learners understand the data before prompting.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

### Step 3: Find top risks

**Open this file:** `artifacts/work-documents/excel-readiness-workbook.xlsx`

**Prompt to use:**

```text
Analyze the Readiness Metrics worksheet. Identify the top three risk scores, explain the likely operational concern for each, and recommend the first follow-up question for the owner.
```

**Expected result:** A ranked risk analysis grounded in the spreadsheet.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

### Step 4: Summarize trends

**Open this file:** `artifacts/work-documents/excel-readiness-workbook.xlsx`

**Prompt to use:**

```text
Summarize what the workbook says about open actions and priority. Identify patterns by facility and workstream. Do not use external data.
```

**Expected result:** Workbook trend summary without web grounding.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

### Step 5: Create a decision brief

**Open this file:** `artifacts/work-documents/excel-industry-brief.docx`

**Prompt to use:**

```text
Using the workbook analysis, draft a decision brief with: executive summary, top risks, recommended action, owner, and what needs human validation.
```

**Expected result:** Excel insight becomes a Word-ready brief.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

### Step 6: Create slide content

**Open this file:** `artifacts/work-documents/excel-executive-briefing.pptx`

**Prompt to use:**

```text
Turn the workbook findings into a slide outline with one headline insight, three supporting data points, and speaker notes for an energy operations leader.
```

**Expected result:** Excel analysis becomes presentation-ready content.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

### Step 7: GCC fallback close

**Open this file:** `Presenter PPTX`

**Prompt to use:**

```text
No prompt. Say: In a Copilot-enabled tenant, I would ask these questions directly in Excel. Here, I am showing the workflow and expected result using sample artifacts.
```

**Expected result:** Presenter avoids unavailable Excel Copilot features.

**Presenter note:** If Copilot is unavailable, read the prompt aloud, show the source file, and describe the expected output instead of demonstrating unavailable GCC functionality.

## Final human-review checklist

Before sharing any generated output, verify:

- The output is grounded only in the provided files.
- No customer confidential data or real tenant details were introduced.
- Any assumption is marked `[VERIFY]`.
- The tone is appropriate for the audience.
- The feature shown or described is available in the tenant being used.

## Cleanup

Remove any non-public presenter files after delivery. Keep this repository public-safe.
