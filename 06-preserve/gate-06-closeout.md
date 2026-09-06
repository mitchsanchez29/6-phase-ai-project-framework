# Gate 6 — Preservation Closeout

## 1. Purpose

Gate 6 formally closes the current project lifecycle iteration after the accepted project state has been preserved.

The purpose of this gate is to confirm that:

* The accepted project state has been preserved.
* The final version is identifiable.
* Required artifacts are available.
* The project is recoverable.
* Documentation corresponds to the preserved state.
* The lifecycle record is complete.
* Future changes can begin from a known baseline.

Gate 6 answers:

**IS THE COMPLETED PROJECT SAFELY PRESERVED AND READY FOR FUTURE USE OR CHANGE?**

---

## 2. Entry Criteria

Gate 6 may begin when:

* PRESERVE completion criteria have been reviewed.
* The final accepted version has been identified.
* Required project artifacts have been preserved.
* Documentation has been preserved.
* Version information has been recorded.
* Recoverability has been considered or verified.
* Maintenance ownership has been identified when applicable.

---

## 3. Gate Criteria

### Final Project State

* [ ] The accepted implementation is clearly identified.
* [ ] The preserved version is clearly identifiable.
* [ ] The final project state matches the accepted state.
* [ ] No unintended changes remain in the preserved baseline.

### Source and Artifacts

* [ ] Source code is preserved.
* [ ] Required project files are preserved.
* [ ] Required configuration information is preserved.
* [ ] Required assets are preserved.
* [ ] Required tests or test artifacts are preserved when applicable.

### Documentation

* [ ] Final documentation is preserved.
* [ ] Documentation matches the preserved implementation.
* [ ] Known limitations are documented.
* [ ] Important decisions are preserved.
* [ ] Recovery or deployment information is available when applicable.

### Version Control

* [ ] Version history is available.
* [ ] The preserved version has an identifiable commit, tag, or release.
* [ ] Important changes are traceable.
* [ ] The repository state is understandable.

### Security

* [ ] Secrets are not improperly stored.
* [ ] Sensitive information is appropriately handled.
* [ ] Access requirements are understood.
* [ ] Preservation has not introduced an unacceptable security exposure.

### Recoverability

* [ ] The project can be located.
* [ ] The preserved version can be identified.
* [ ] Required artifacts can be retrieved.
* [ ] Required dependencies are identifiable.
* [ ] Recovery or recreation requirements are documented when applicable.
* [ ] No critical recovery artifact is known to be missing.

### Ownership and Maintenance

When applicable:

* [ ] Repository ownership is understood.
* [ ] Maintenance responsibility is identified.
* [ ] Deployment responsibility is identified.
* [ ] Access responsibility is understood.
* [ ] Future change responsibility is understood.

### Lifecycle Record

* [ ] Gate decisions have been recorded.
* [ ] Acceptance status has been recorded.
* [ ] Important risks have been recorded.
* [ ] Important deviations have been recorded.
* [ ] Final project status has been recorded.

---

## 4. Gate Outcomes

### PASS

The project lifecycle iteration has been successfully completed.

The preserved project becomes the:

**PRESERVED BASELINE**

The project may enter maintenance, operation, or a future lifecycle iteration.

---

### CONDITIONAL PASS

The lifecycle may be closed when:

* Remaining issues do not compromise preservation or recovery.
* The issues are documented.
* Accepted risks are recorded.
* Responsible parties understand the remaining conditions.

---

### FAIL

The lifecycle must remain open.

The project returns to the appropriate phase required to resolve the issue.

Possible return paths include:

**GATE 6 → PRESERVE**

when preservation is incomplete.

**GATE 6 → DOCUMENT**

when required documentation is missing or inaccurate.

**GATE 6 → VALIDATE**

when the preserved state does not correspond to the accepted implementation.

**GATE 6 → BUILD**

when the implementation itself must be corrected.

**GATE 6 → DESIGN**

when the underlying design must be reconsidered.

**GATE 6 → THINK**

when requirements or intended outcomes must be reconsidered.

---

## 5. Final Closeout Record

Record the final lifecycle decision:

**Gate Status:** PASS / CONDITIONAL PASS / FAIL

**Project Status:** CLOSED / CONDITIONALLY CLOSED / OPEN

**Date:**

**Reviewer:**

**Preserved Version:**

**Commit / Tag / Release:**

**Repository:**

**Acceptance Status:**

**Outstanding Issues:**

**Accepted Risks:**

**Known Limitations:**

**Maintenance Owner:**

**Required Follow-up:**

**Notes:**

---

## 6. Preservation Baseline

When Gate 6 passes, the preserved project becomes the:

**PRESERVED BASELINE**

The PRESERVED BASELINE represents the known, accepted, documented, and recoverable state of the project at the time of lifecycle closeout.

Future changes should begin from this baseline rather than modifying an unidentified or undocumented state.

---

## 7. Lifecycle Closeout

A successful Gate 6 means the current lifecycle iteration is formally closed.

Closure does not mean the project can never change.

It means the current state has been:

**DEFINED → DESIGNED → BUILT → VALIDATED → DOCUMENTED → PRESERVED**

and the result has been formally recorded.

---

## 8. Future Change

When a future change is required, the project may begin a new lifecycle iteration.

The new iteration should reference the PRESERVED BASELINE.

Examples:

### New requirement

Return to:

**THINK**

### Major architectural change

Return to:

**DESIGN**

### Implementation change

Return to:

**BUILD**

### Verification of an existing or changed implementation

Return to:

**VALIDATE**

### Documentation-only change

Return to:

**DOCUMENT**

### Preservation of a new version

Return to:

**PRESERVE**

The framework therefore supports controlled iteration rather than uncontrolled modification.

---

## 9. Final Lifecycle

A completed lifecycle follows:

**PHASE 0 — PROJECT INITIATION**

↓

**PHASE 1 — THINK**

↓

**GATE 1 — REQUIREMENTS READINESS**

↓

**PHASE 2 — DESIGN**

↓

**GATE 2 — DESIGN READINESS**

↓

**PHASE 3 — BUILD**

↓

**GATE 3 — BUILD READINESS**

↓

**PHASE 4 — VALIDATE**

↓

**GATE 4 — ACCEPTANCE**

↓

**PHASE 5 — DOCUMENT**

↓

**GATE 5 — HANDOFF READINESS**

↓

**PHASE 6 — PRESERVE**

↓

**GATE 6 — PRESERVATION CLOSEOUT**

↓

**PRESERVED BASELINE**

---

## 10. Framework Principle

The lifecycle is controlled by:

**PHASES**

The transitions are controlled by:

**GATES**

Knowledge is transferred through:

**ARTIFACTS**

Quality is established through:

**VALIDATION AND EVIDENCE**

The resulting project state is protected through:

**VERSION CONTROL AND PRESERVATION**

AI tools perform work within the lifecycle.

The framework controls how that work progresses.

---

## Final Exit

When Gate 6 receives a PASS decision:

**THE CURRENT PROJECT LIFECYCLE ITERATION IS CLOSED.**

The PRESERVED BASELINE becomes the authoritative starting point for future work.
