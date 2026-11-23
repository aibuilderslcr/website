# Website issues and feature requests

Use [GitHub Issues](https://github.com/aibuilderslcr/website/issues) to suggest features, report bugs, and track work on [aibuilderslcr.co.uk](https://aibuilderslcr.co.uk). A GitHub account is required to submit or comment.

## Submit a request

1. Search [all issues, including closed ones](https://github.com/aibuilderslcr/website/issues?q=is%3Aissue). Add a thumbs-up reaction or useful context to an existing request instead of opening a duplicate.
2. Choose [Feature request](https://github.com/aibuilderslcr/website/issues/new?template=feature_request.yml) or [Bug report](https://github.com/aibuilderslcr/website/issues/new?template=bug_report.yml).
3. Complete the form. Describe the problem and the outcome you need; you do not need to know how to implement it.
4. Follow the issue for questions and progress updates.

Keep each issue focused on one problem or proposal. Issues and attachments are public, so remove personal information and secrets.

## Manage the backlog

New reports receive a type label and `status: triage` automatically from their form. Maintainers manage the remaining labels and assignments in GitHub.

| Label | Meaning |
| --- | --- |
| `bug` | Something is broken, confusing, or inaccessible. |
| `enhancement` | A feature request or improvement. |
| `status: triage` | Needs review, clarification, and a decision. |
| `status: planned` | Accepted and ready to be picked up; not a delivery-date promise. |
| `status: in progress` | Someone is actively working on it. |
| `status: blocked` | Cannot proceed; a comment should explain the dependency. |
| `priority: high` | Major impact or an urgent problem. |
| `priority: medium` | Useful work with normal priority. |
| `priority: low` | A small improvement that can wait. |

Use one status label on each open issue and at most one priority label. Keep the type label throughout. Add existing labels such as `accessibility`, `documentation`, `good first issue`, or `help wanted` when useful.

During triage:

1. Check for duplicates and ask for missing information. Use `question` while waiting for clarification.
2. Decide whether the request belongs in the website backlog. For accepted work, clarify the acceptance criteria, set a priority, and replace `status: triage` with `status: planned`.
3. Assign an owner when work starts and replace the status with `status: in progress`. If work is blocked, use `status: blocked` and explain what is needed to continue.
4. Link the implementation pull request with `Closes #123` so GitHub closes the issue when the change merges into the default branch. Check the acceptance criteria and remove the status label when closing it.
5. Close duplicates as **not planned**, add `duplicate`, and link the original. For declined requests, explain the decision, add `wontfix`, and close as **not planned**. Completed work closes as **completed**.

Reopened issues return to `status: triage` unless a maintainer has already agreed the next step. Status changes, priority, and ownership are maintained manually; the forms only apply the initial labels.

## Useful views

- [All open issues](https://github.com/aibuilderslcr/website/issues)
- [Needs triage](https://github.com/aibuilderslcr/website/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22status%3A%20triage%22)
- [Planned work](https://github.com/aibuilderslcr/website/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22status%3A%20planned%22)
- [In progress](https://github.com/aibuilderslcr/website/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22status%3A%20in%20progress%22)
- [Blocked](https://github.com/aibuilderslcr/website/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22status%3A%20blocked%22)
- [Feature requests, most thumbs-up first](https://github.com/aibuilderslcr/website/issues?q=is%3Aissue%20is%3Aopen%20label%3Aenhancement%20sort%3Areactions-%2B1-desc)
- [Open bugs](https://github.com/aibuilderslcr/website/issues?q=is%3Aissue%20is%3Aopen%20label%3Abug)

## Contribute a change

Comment on the issue before starting so maintainers can coordinate work. Keep changes focused, link the issue in your pull request, and include a short explanation of the result and how you checked it.

For site changes, run `bun run build` and `bun run lint` before submitting. See the [README](README.md) for local setup.
