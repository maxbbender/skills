# Triage Labels

The skills speak in terms of five canonical triage roles. This file maps those roles to the actual label strings used in this repo's issue tracker.

| Label in mattpocock/skills | Label in our tracker | Meaning                                  |
| -------------------------- | -------------------- | ---------------------------------------- |
| `needs-triage`             | `needs-triage`       | Maintainer needs to evaluate this issue  |
| `needs-info`               | `needs-info`         | Waiting on reporter for more information |
| `ready-for-agent`          | `ready-for-agent`    | Fully specified, ready for an AFK agent  |
| `ready-for-human`          | `ready-for-human`    | Requires human implementation            |
| `wontfix`                  | `wontfix`            | Will not be actioned                     |

## Category and modifier labels

Every triaged issue carries one category label beside its state label. Modifiers are optional.

| Label          | Kind     | Meaning                                                              |
| -------------- | -------- | -------------------------------------------------------------------- |
| `bug`          | category | Something is broken                                                  |
| `enhancement`  | category | New feature or improvement                                           |
| `chore`        | category | Maintenance with no user-visible change (dependencies, CI, refactor) |
| `spec`         | modifier | A parent issue that `/to-tickets` slices; never a task               |
| `urgent`       | modifier | Production is broken; the issue jumps the frontier                   |
| `area:<name>`  | modifier | The part of the codebase touched                                     |

When a skill mentions a role (e.g. "apply the AFK-ready triage label"), use the corresponding label string from this table.

Edit the "Label in our tracker" column to match whatever vocabulary you actually use.
