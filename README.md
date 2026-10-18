# SteamWiz/.github

Org-wide defaults for SteamWiz repositories. GitHub uses a file here only when a repo doesn't have its own version of it.

| File | What |
|---|---|
| `ISSUE_TEMPLATE/bug.yml` | Bug form. Sets issue type **Bug** and adds the issue to the [SteamWiz Backlog](https://github.com/orgs/SteamWiz/projects/2) |
| `ISSUE_TEMPLATE/feature.yml` | Feature form (user-visible behaviour). Type **Feature**, added to the Backlog |
| `ISSUE_TEMPLATE/task.yml` | Task form (chores, docs, dependencies, CI, refactors, specs/decisions). Type **Task**, added to the Backlog |
| `ISSUE_TEMPLATE/config.yml` | Blank issues stay enabled for quick notes |
| `pull_request_template.md` | Default PR description: linked issue, what changed, how it was checked |

Conventions:

- The **issue type** carries the kind of work (Bug / Feature / Task / Epic). There are no `bug` or `enhancement` labels. Epics are created by the planner, so they have no form.
- The issue description is the living spec. The planner turns "Done when" / "Fixed when" into acceptance criteria and sets the board Status and order.
- The **Backlog board's manual order** is the priority order.

These defaults only take effect while this repository is **public**.
