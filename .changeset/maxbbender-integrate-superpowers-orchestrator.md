---
"mattpocock-skills": minor
---

Fork-only: integrate with the maxbbender superpowers fork and the `/orchestrator` session skill so one lifecycle owner exists per stage.

- `to-spec` labels the published issue `spec` (a parent, never a task) instead of `ready-for-agent`, and self-reviews the body for placeholders, consistency, scope, and ambiguity before handing off to `/to-tickets`.
- `setup-matt-pocock-skills` label seed and `triage` gain the `chore` category and the `spec` / `urgent` / `area:<name>` modifiers the orchestrator's frontier query reads.
- `tdd` becomes the test-quality reference that `superpowers:test-driven-development` points at; its description no longer triggers on "build a feature".
- `diagnosing-bugs` triggers on bugs that have no reproducing command yet (reports, tickets, flakes, perf); in-loop failures go to `superpowers:systematic-debugging`. Phase 5 runs the superpowers TDD loop.
- `ask-matt` routes the ticket frontier through `/orchestrator`, with `/implement` as the builder's semantics.
