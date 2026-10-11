# AI-Use Log

## Responsibility statement

This log records actual AI assistance used for SWE 525 Lab 8.

On October 11, 2026, I submitted three GitHub-related tasks in one message to Perplexity. The assistant answered them in one exchange and used the GitHub connector to inspect the published repository.

The three task records below belong to that exchange. 
I read all the responses and confirmed that I accepted all three tasks and the follow-up assistance. I did not reject any suggestions.

My requests for clarification and formatting changes refined the documentation rather than rejecting the assistance.

I remain responsible for reviewing the suggestions and ensuring that the final documentation accurately represents my work.

## Exchange 1 — Three GitHub-related tasks

- Date: October 11, 2026
- Assistant: Perplexity
- Repository: https://github.com/JoMEngAI/swe325_525-github-ai-practice
- Issue: https://github.com/JoMEngAI/swe325_525-github-ai-practice/issues/1

### Task 1 — Explanation

#### Purpose

Understand the GitHub objects used in the assignment.

#### Prompt

For my SWE 525 GitHub Issues lab, explain the difference between a repository, issue, branch, commit, pull request, and default branch. Connect the concepts to a documentation-only repository containing README.md, workflow-notes.md, and ai-log.md. Use GitHub Desktop and browser terminology only; do not give terminal commands.

#### Useful output

The assistant explained how the repository, issue, branch, commit, pull request, and default branch relate to the documentation workflow.

It also explained the difference between committing locally and pushing changes to GitHub.

#### Decision and reason

Accepted. The explanation clarified the purpose of each object and helped me understand how the workflow steps fit together.

- Accepted: The concept explanations and their connection to my documentation files.
- Revised: No substantive concept changes.
- Rejected: None.

#### Related GitHub URL

https://github.com/JoMEngAI/swe325_525-github-ai-practice/issues/1

### Task 2 — README improvement

#### Purpose

Review the actual README and propose a specific improvement.

#### Prompt summary

Review my current README for clarity, propose one specific improvement, keep the repository documentation-only, avoid claims about unfinished work, and explain why the improvement helps.

#### Useful output

The assistant identified the student-identification placeholder and proposed replacing it with JoMEngAI.

It also identified a table-formatting problem. Follow-up guidance restored Markdown headings and a correctly formatted table.

#### Decision and reason

Accepted. Clear identification and structured formatting make the README easier to understand and inspect.

- Accepted: The identification correction and formatting assistance.
- Revised: I requested Markdown headings and restored table formatting after initially requesting removal of heading symbols. This was a presentation refinement rather than a rejection of the assistance.
- Rejected: None.

#### Related GitHub URL

https://github.com/JoMEngAI/swe325_525-github-ai-practice/blob/feature/github-ai-workflow/README.md

### Task 3 — Acceptance-criteria review

#### Purpose

Prepare a pull-request verification checklist matching the actual issue.

#### Prompt summary

Review my actual acceptance criteria, produce a matching checklist, identify criteria that require post-merge verification, and use GitHub Desktop and browser instructions only.

#### Useful output

The assistant mapped the checklist to AC1 through AC7.

It explained that AC2 includes confirming the feature branch remains after merging and AC7 includes confirming the merged files on main.

#### Decision and reason

Accepted. The checklist organizes the work into observable requirements and separates pre-merge readiness from final-state verification.

- Accepted: The checklist and the distinction between pre-merge and post-merge checks.
- Revised: Presentation was aligned with the Markdown documentation.
- Rejected: None.

#### Related GitHub URL

https://github.com/JoMEngAI/swe325_525-github-ai-practice/issues/1

## Follow-up exchanges — Formatting, repository review, and reflection

- Date: October 11, 2026
- Assistant: Perplexity

### Purpose and prompt summaries

I asked the assistant to retrieve actual GitHub links, restore Markdown headings and tables, inspect the repository for remaining problems

I then confirmed that I accepted all tasks and exchanges and supplied my own views for the reflection answers.

I also clarified that I wanted to perform the GitHub actions myself using step-by-step instructions rather than have the assistant make repository changes this way I learn.

The assistant explained how editing and saving Markdown in VS Code relates to committing and pushing through GitHub Desktop.

It taught me the VS Code Markdown preview shortcut, Shift+Command+V.

### Decision and reason

Accepted. The detailed structure, explanations, and follow-up verification helped me understand the process and express my thoughts clearly.

- Accepted: The formatting corrections, workflow explanations, evidence-link assistance, and structured reflection support.
- Revised: Presentation preferences and the instruction-only workflow were clarified through follow-up requests.
- Rejected: None.

### Related GitHub URL

https://github.com/JoMEngAI/swe325_525-github-ai-practice/tree/feature/github-ai-workflow

## Reflection

### 1. Which GitHub action or object was most useful to you, and why?

The most useful GitHub action to understand was committing changes to Markdown files that I edited in VS Code. This connected the documentation I was writing with the version history recorded in GitHub.

I especially valued learning how Markdown headings and tables affect the rendered documentation and how to use Shift+Command+V to preview a Markdown file in VS Code.

This helped me understand that editing, previewing, saving, committing, and pushing are different steps, each with its own purpose.

### 2. Which AI suggestion did you accept, and what made it useful?

I accepted all the suggestions across the three tasks and follow-up exchanges.

The concept explanations made the GitHub objects easier to understand. The README suggestions improved clarity and presentation. The acceptance checklist organized the assignment into requirements that could be checked.

The detailed steps and copy-and-paste examples helped me connect the explanations to the assignment. I also appreciated how the assistant structured my thoughts while helping me express my own understanding.

### 3. Which AI suggestion did you revise or reject, and why?

I did not reject any suggestions because I agreed with the assistance.

I refined the presentation through follow-up requests, including asking to restore Markdown heading symbols and table formatting after initially requesting their removal.

That change clarified how I wanted the documentation presented. It was not a rejection of the underlying explanations or workflow guidance.

### 4. What did you verify yourself instead of trusting the AI?

I read every word of the responses and considered whether the explanations matched what I was trying to accomplish.

When I needed more detail or confirmation, I asked follow-up questions and requested that the assistant inspect GitHub or explain the reasoning further.

My own review consisted of reading, evaluating, and questioning the guidance. Repository checks performed through the connector were assistant-assisted verification rather than checks I independently performed.

### 5. What would you change in your GitHub workflow next time?

I would be more thorough in my initial prompts and provide better context, including my current step, tools, constraints, desired formatting, and what I have already completed.

I would ask clearer questions and request explanations and verification where needed.

Better prompting would help the assistant guide me more accurately and help me understand the process rather than only follow instructions.