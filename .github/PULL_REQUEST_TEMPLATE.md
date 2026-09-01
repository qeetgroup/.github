## What this changes

<!-- One paragraph. What is different after this merges, and why. -->

## Linked issue

<!-- Closes qeetgroup/qeet-id-<repo>#NNN — required. Work without an issue is not tracked,
     and nothing appears on the delivery board without one. -->

Closes #

## Contract impact

<!-- Delete the lines that do not apply. -->

- [ ] **No contract change** — internal only
- [ ] Changes an API request or response shape
- [ ] Changes a token claim, session or cookie behaviour
- [ ] Changes a webhook payload or event name
- [ ] Changes the database schema → add the `db-migration` label
- [ ] **Breaks a published contract** → add the `breaking-change` label and check
      `qeet-id-context/CHANGE-MATRIX.md` for the consumers this reaches

## How this was verified

<!-- What you actually ran or clicked. "Tests pass" on its own is not verification —
     say which behaviour you observed. -->

## Rollback

<!-- Required for anything labelled db-migration, breaking-change, or Risk: High or above.
     How is this undone in production if it goes wrong? -->

---

## Definition of Done

- [ ] Every acceptance criterion on the linked issue is met
- [ ] CI is green — typecheck, lint, architecture fitness, tests, build
- [ ] Reviewed and approved by someone who did not write it
- [ ] **QA Status is `Passed`**, or `Not Required` as agreed at planning
- [ ] Docs updated where behaviour changed, including an ADR for an architectural decision
- [ ] No new secret, token or personal data reaches a log, an error message or the browser
- [ ] Anything touching auth, tokens, sessions or crypto has had a security reviewer

> `Done` on the board means deployed **and verified in production** — not merged.
