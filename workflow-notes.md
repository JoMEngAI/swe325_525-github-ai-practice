# GitHub Workflow Notes

## Repository information

| Item | Value |
| --- | --- |
| Repository | [swe325_525-github-ai-practice](https://github.com/JoMEngAI/swe325_525-github-ai-practice) |
| Default branch | `main` |
| Feature branch | `feature/github-ai-workflow` |
| Issue number | 1 |
| Issue title | Document GitHub workflow with AI assistance |
| Issue URL | https://github.com/JoMEngAI/swe325_525-github-ai-practice/issues/1 |

### Issue purpose

Define the documentation work, acceptance criteria, tasks, and verification plan for SWE 525 Lab 8.

## GitHub concepts

### Repository

A repository stores project files and their version history. This repository contains Markdown documentation for the assignment.

### Issue

An issue records a task, problem, or proposed improvement. My issue defines the assignment work and the acceptance criteria used to check it.

### Branch

A branch provides a separate line of development. I use `feature/github-ai-workflow` to prepare the documentation without directly changing `main`.

### Commit

A commit records a snapshot of selected changes. Specific commit messages explain the purpose of each change.

### Pull request

A pull request proposes merging changes from one branch into another. It provides a place to inspect the changes, discuss them, and record review feedback.

### Default branch

The default branch is the repository's primary branch. In this repository, it is `main`. It will contain the reviewed documentation after the pull request is merged.

## Workflow sequence

1. Create and publish the repository.
2. Create an issue defining the work and acceptance criteria.
3. Create `feature/github-ai-workflow` from `main`.
4. Improve `README.md` and record the change in a meaningful commit.
5. Create `workflow-notes.md` and record the change in a meaningful commit.
6. Complete the required GitHub-related AI tasks.
7. Save substantive AI-task records and reflections in `ai-log.md`.
8. Push the feature-branch commits to GitHub.
9. Open a pull request from the feature branch into `main`.
10. Add the actual pull-request URL to these notes.
11. Review the documentation against the acceptance criteria.
12. Respond to feedback and revise the documentation.
13. Merge the pull request into `main`.
14. Retain the feature branch and verify the final repository state.

## Evidence links

### Repository

https://github.com/JoMEngAI/swe325_525-github-ai-practice

### Issue

https://github.com/JoMEngAI/swe325_525-github-ai-practice/issues/1

### Feature branch

https://github.com/JoMEngAI/swe325_525-github-ai-practice/tree/feature/github-ai-workflow

### Meaningful commit 1 — Clarify repository purpose

https://github.com/JoMEngAI/swe325_525-github-ai-practice/commit/0d8de69452775181bb7732af3fd5bcf3ab403853

### Meaningful commit 2 — Document branch and pull request workflow

https://github.com/JoMEngAI/swe325_525-github-ai-practice/commit/5738fde27d793669f482282ce19e9031df4d0bc1

### Meaningful commit 3 — Add AI-use record fixed

https://github.com/JoMEngAI/swe325_525-github-ai-practice/commit/27187c978b8c889de216623f0377808afce1cfbf

This commit added substantive AI-log content after the earlier commit created an empty log file.

### Finalized AI decisions and reflections

https://github.com/JoMEngAI/swe325_525-github-ai-practice/commit/72faeb5c4594566358ade3d08048f89bae576fb4

### Markdown formatting revision

https://github.com/JoMEngAI/swe325_525-github-ai-practice/commit/2bab4b1dac02cee1df5645a28cc4993910ae146e

### Pull request

https://github.com/JoMEngAI/swe325_525-github-ai-practice/pull/2

### Default-branch history

https://github.com/JoMEngAI/swe325_525-github-ai-practice/commits/main

## How the workflow objects relate

The issue defines what should be completed and how success will be checked.

The feature branch keeps the assignment changes separate from `main` during development.

The commits record meaningful steps in producing and revising the documentation.

The pull request gathers the proposed changes for review and references the issue.

The review checks the changes against the acceptance criteria and records feedback.

Merging the pull request brings the reviewed documentation into `main`.

The issue, commit history, pull request, and retained feature branch provide evidence of the workflow.

## Markdown, VS Code, and GitHub

The `.md` files contain documentation written in Markdown.

I use VS Code to edit and save the files. The Markdown preview shortcut, Shift+Command+V, helps me inspect the rendered headings, tables, and lists.

GitHub Desktop records saved file changes in commits. Pushing publishes those commits to GitHub, where the Markdown files can be viewed and reviewed.

Previewing, saving, committing, and pushing are separate steps.