# W6

## Instructions

1. **Create a testing plan** for your app. Use [`_template/test-plan-template.md`](_template/test-plan-template.md). For each functional requirement from your W2 requirements table, write at least one test case: an ID, the requirement it tests, a short description, the steps to carry it out, and the expected result.
2. **Cover your non-functional requirements too** — each NFR needs a test you can actually measure (e.g. *"note list loads in under 1 second with 500 notes"*), not just "the app is fast".
3. **Start with your *Must* requirements** — use your MoSCoW priorities from W5. Every *Must* requirement needs at least one test case; *Should* and *Could* follow if time allows.
4. **Check coverage** — every requirement ID should appear in at least one test case. List any requirement you can't yet test and why.
5. Bring your test plan to the next session for discussion.

## Writing good test cases

- **One behaviour per test** — if a test checks two things, split it.
- **Steps anyone can follow** — someone outside your team should be able to run the test from your steps alone.
- **Expected result is observable** — describe what the user sees or what is stored, so pass/fail is unambiguous.
- **Traceable** — the Requirement column links each test back to an FR/NFR, and through it to a use case and persona.

## `_template/` — test plan template

- `_template/test-plan-template.md` — the test case table, with a Result column to fill in once you start testing your vibe-coded app.
