# Gate 3 — Build Readiness

## 1. Purpose

Gate 3 determines whether the BUILD phase has produced a sufficiently complete and stable implementation for formal validation.

The purpose of this gate is to prevent incomplete, unstable, or poorly documented implementations from being passed to VALIDATE.

This gate does not determine whether the system fully satisfies the project requirements.

That determination belongs to Phase 4 — VALIDATE.

---

## 2. Entry Criteria

Gate 3 may begin when:

* BUILD completion criteria have been reviewed.
* The implementation is available for testing.
* Required build artifacts have been prepared.
* Known issues have been documented.
* Design deviations have been identified and documented.

---

## 3. Gate Criteria

### Implementation Completeness

* [ ] Approved core functionality has been implemented.
* [ ] Required features have been implemented.
* [ ] Major components are present.
* [ ] Required integrations are implemented.
* [ ] Required configurations are in place.

### Design Alignment

* [ ] Implementation follows the approved DESIGN BASELINE.
* [ ] Major architectural decisions match the approved design.
* [ ] Major deviations are documented.
* [ ] Architectural deviations have been reviewed when required.

### Functional Readiness

* [ ] The implementation can be executed or accessed.
* [ ] Core functionality can be tested.
* [ ] Required user flows can be exercised.
* [ ] Required data flows can be tested.
* [ ] Required integrations can be tested.

### Security Readiness

* [ ] Required security controls have been implemented.
* [ ] Secrets are not exposed in source code.
* [ ] Authentication is implemented when applicable.
* [ ] Authorization is implemented when applicable.
* [ ] Basic input validation is implemented.
* [ ] Known security issues are documented.

### Build Testing

* [ ] Appropriate build-level tests have been performed.
* [ ] Critical implementation errors have been addressed.
* [ ] Known test failures are documented.
* [ ] Blocking defects have been resolved or explicitly escalated.

### Documentation and Traceability

* [ ] Build notes are available.
* [ ] Known issues are documented.
* [ ] Design deviations are documented.
* [ ] Requirements traceability has been updated where necessary.
* [ ] VALIDATE has sufficient information to test the implementation.

### Validation Readiness

* [ ] The implementation is ready for formal validation.
* [ ] Test instructions are available when required.
* [ ] Required test data or test accounts are available when applicable.
* [ ] VALIDATE does not need to reconstruct the implementation from AI conversations.

---

## 4. Gate Outcomes

### PASS

The BUILD phase is sufficiently complete.

The project may proceed to:

**Phase 4 — VALIDATE**

---

### CONDITIONAL PASS

The project may proceed to VALIDATE only when:

* Remaining issues are non-blocking.
* The issues are explicitly documented.
* The responsible person accepts the remaining risk.
* The issues do not prevent meaningful validation.

---

### FAIL

The project must not proceed to VALIDATE.

The project returns to:

**Phase 3 — BUILD**

or, when the problem originates from the approved design:

**Phase 2 — DESIGN**

If the problem originates from requirements, the project may return to:

**Phase 1 — THINK**

---

## 5. Gate Decision Record

Record the decision:

**Gate Status:** PASS / CONDITIONAL PASS / FAIL

**Date:**

**Reviewer:**

**Outstanding Issues:**

**Known Defects:**

**Required Actions:**

**Accepted Risks:**

**Design Deviations:**

**Notes:**

---

## 6. Re-entry

A failed Gate 3 does not terminate the project.

The project returns to the appropriate phase or activity required to resolve the identified issue.

After the issue is resolved, Gate 3 must be reviewed again.

---

## 7. Exit

Gate 3 is complete when the gate decision has been recorded.

If approved:

**BUILD → GATE 3 → VALIDATE**

The implementation submitted to VALIDATE is called the:

**BUILD CANDIDATE**

The BUILD CANDIDATE becomes the subject of formal validation in Phase 4.

---

## 8. Important Boundary

Gate 3 does not approve the final quality or acceptance of the system.

It only determines whether the implementation is sufficiently ready to be formally tested and evaluated.

Final validation and acceptance belong to:

**Phase 4 — VALIDATE**
