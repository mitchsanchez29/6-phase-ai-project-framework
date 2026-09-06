# Gate 4 — Acceptance

## 1. Purpose

Gate 4 determines whether the validated implementation satisfies the approved requirements, success criteria, quality expectations, and acceptance conditions.

The purpose of this gate is to make the acceptance decision explicit and evidence-based before the project moves to DOCUMENT.

This gate represents the formal decision point between:

**VALIDATION**

and

**DOCUMENTATION**

---

## 2. Entry Criteria

Gate 4 may begin when:

* VALIDATE completion criteria have been reviewed.
* Required validation activities have been performed.
* Validation evidence has been recorded.
* Significant defects have been documented.
* Blocking defects have been resolved or formally addressed.
* Acceptance criteria have been evaluated.

---

## 3. Gate Criteria

### Requirements Acceptance

* [ ] Approved functional requirements have been validated.
* [ ] Approved non-functional requirements have been validated when applicable.
* [ ] No critical requirement has been silently changed or removed.
* [ ] Requirements validation results are documented.

### Success Criteria

* [ ] Approved success criteria have been evaluated.
* [ ] Expected outcomes have been compared with actual outcomes.
* [ ] Evidence supports the acceptance decision.

### Functional Validation

* [ ] Critical user workflows have passed.
* [ ] Core functionality has passed.
* [ ] Important edge cases have been evaluated.
* [ ] Error handling has been evaluated where applicable.

### Integration Validation

When applicable:

* [ ] Required integrations have passed.
* [ ] Data synchronization has been verified.
* [ ] External service behavior has been verified.
* [ ] Failure scenarios have been considered.

### Security Validation

When applicable:

* [ ] Required security controls have been evaluated.
* [ ] Critical security issues have been resolved.
* [ ] No known unacceptable security exposure remains.

### Defects

* [ ] Critical defects are resolved.
* [ ] Blocking defects are resolved.
* [ ] Remaining defects are documented.
* [ ] Accepted defects have an identified impact.
* [ ] Any accepted risk has an appropriate owner or decision.

### Evidence

* [ ] Validation results are available.
* [ ] Test results are available.
* [ ] Relevant screenshots, logs, reports, or other evidence are available when appropriate.
* [ ] The acceptance decision can be supported by documented evidence.

### Documentation Readiness

* [ ] Final system behavior is sufficiently understood.
* [ ] Known limitations are documented.
* [ ] Important operational information is available.
* [ ] Phase 5 — DOCUMENT has sufficient information to begin.

---

## 4. Gate Outcomes

### PASS

The implementation has satisfied the required validation and acceptance criteria.

The project may proceed to:

**Phase 5 — DOCUMENT**

---

### CONDITIONAL PASS

The implementation may proceed when:

* Remaining issues are non-blocking.
* Remaining limitations are documented.
* Accepted risks are explicitly recorded.
* The responsible person accepts the remaining issues.

The conditions must be recorded before proceeding.

---

### FAIL

The implementation has not satisfied the required acceptance criteria.

The project must return to the appropriate phase.

Possible return paths:

**GATE 4 → VALIDATE**

when additional testing or evidence is required.

**GATE 4 → BUILD**

when implementation defects must be corrected.

**GATE 4 → DESIGN**

when the approved design is inadequate.

**GATE 4 → THINK**

when the underlying requirements or intended outcome must be reconsidered.

---

## 5. Acceptance Decision

Record the final decision:

**Acceptance Status:** ACCEPTED / CONDITIONALLY ACCEPTED / REJECTED

**Date:**

**Reviewer:**

**Acceptance Criteria Summary:**

**Outstanding Issues:**

**Accepted Risks:**

**Known Limitations:**

**Required Actions:**

**Evidence References:**

**Notes:**

---

## 6. Re-entry

A failed Gate 4 does not terminate the project.

The project returns to the phase responsible for resolving the identified issue.

After the issue has been resolved, the affected validation activities must be repeated.

Gate 4 must then be reviewed again.

---

## 7. Evidence-Based Acceptance

Acceptance must be based on documented evidence.

The following do not constitute sufficient acceptance by themselves:

* AI approval
* Developer confidence
* "It works on my machine"
* Completion of coding tasks
* Passing only one type of test
* A successful demonstration without requirements comparison

Acceptance should be based on the project's defined requirements, success criteria, validation results, and appropriate human judgment.

---

## 8. Human Acceptance

For projects involving meaningful business, financial, operational, security, or user impact, an appropriate human reviewer should participate in the acceptance decision.

The required level of human review should be proportional to project risk.

The framework does not require human review for every minor change, but critical decisions must not be delegated blindly to AI.

---

## 9. Exit

Gate 4 is complete when the acceptance decision has been recorded.

If approved:

**VALIDATE → GATE 4 → DOCUMENT**

The accepted implementation becomes the:

**VALIDATED RELEASE CANDIDATE**

---

## 10. Important Boundary

Gate 4 determines whether the validated implementation is accepted.

It does not replace documentation.

After acceptance:

**DOCUMENT** records how the system works, how it should be operated, maintained, and handed off.

**PRESERVE** ensures the source, history, versions, and recoverable project state are retained.

---

## Phase Exit

Gate 4 may proceed to Phase 5 only when the acceptance decision is recorded and all required conditions have been satisfied.

**VALIDATE → GATE 4 → DOCUMENT**
