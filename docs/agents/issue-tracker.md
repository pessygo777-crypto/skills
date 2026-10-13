# Issue tracker: GitHub

Issues and specs live in pessygo777-crypto/skills.

Use the connected GitHub plugin for supported issue operations.
If the gh CLI is installed and authenticated, it may also be used.
Always target pessygo777-crypto/skills explicitly.

## Conventions

- Publish tickets and specs as GitHub issues.
- Read the issue body, labels, and comments before working.
- Apply triage labels from docs/agents/triage-labels.md.
- Link child issues using native sub-issues when supported.
  Otherwise, put "Part of #<parent>" in each child and maintain
  a task list in the parent.
- Record blockers using native dependencies when supported.
  Otherwise, put "Blocked by: #<number>" in the issue body.
- Resolve work by recording the outcome and closing the issue.

## Pull requests as a triage surface

PRs as a request surface: no.

## Wayfinding operations

Use one issue labelled wayfinder:map as the map.
Use linked child issues labelled wayfinder:<type> for
research, prototype, grilling, or task work.
Claim work by assigning the issue to the driving developer.
Record decisions and relevant links in the map.
