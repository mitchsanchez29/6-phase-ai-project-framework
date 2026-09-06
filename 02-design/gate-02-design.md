# Gate 2 — Design Readiness

## 1. Purpose

Gate 2 determines whether the DESIGN phase is complete and sufficiently defined for implementation to begin.

The purpose of this gate is to prevent BUILD from starting with incomplete architecture, unclear technical decisions, missing integrations, or unresolved design risks.

BUILD must not begin until the approved design is sufficiently complete.

---

## 2. Entry Criteria

Gate 2 may begin when:

* DESIGN completion criteria have been reviewed.
* Required DESIGN artifacts have been created.
* Major design decisions have been documented.
* The solution has been reviewed against the approved requirements.

---

## 3. Gate Criteria

### Requirements Alignment

* [ ] All approved requirements have been considered.
* [ ] Requirements can be traced to design decisions.
* [ ] No requirement has been silently changed or removed.

### Architecture

* [ ] Solution architecture is defined when applicable.
* [ ] Major components are identified.
* [ ] Component responsibilities are clear.
* [ ] System boundaries are clear.
* [ ] Major dependencies are identified.
* [ ] Data flow is understood.

### User Experience

When applicable:

* [ ] User journeys are defined.
* [ ] User flows are defined.
* [ ] Navigation and screen structure are clear.
* [ ] Important system and error states are considered.

### Data and System Structure

When applicable:

* [ ] Data entities are defined.
* [ ] Data relationships are defined.
* [ ] Storage approach is defined.
* [ ] State management is defined where required.

### Integrations

When applicable:

* [ ] Required APIs are identified.
* [ ] External services are identified.
* [ ] Authentication requirements are defined.
* [ ] Webhooks or automation requirements are defined.
* [ ] Integration dependencies are documented.

### Security and Reliability

* [ ] Security requirements have been considered.
* [ ] Authentication and authorization are addressed when applicable.
* [ ] Sensitive data handling is defined.
* [ ] Secrets management is considered.
* [ ] Input validation is considered.
* [ ] Error handling is defined.
* [ ] Failure and recovery considerations are documented.
* [ ] Backup or recovery requirements are addressed when applicable.

### Technology Decisions

* [ ] Major technology choices are documented.
* [ ] Technology choices support the requirements.
* [ ] Important trade-offs are understood.
* [ ] Technology decisions are not based solely on AI recommendations.

### Implementation Readiness

* [ ] Implementation has been divided into buildable tasks.
* [ ] Task sequence is defined.
* [ ] BUILD has sufficient technical information to begin.
* [ ] Major implementation decisions do not remain undefined.
* [ ] Known design risks are documented.

---

## 4. Gate Outcomes

### PASS

The DESIGN phase is sufficiently complete.

The project may proceed to:

**Phase 3 — BUILD**

---

### CONDITIONAL PASS

The project may proceed to BUILD only when:

* Remaining issues are non-critical.
* The issues are explicitly documented.
* The responsible person accepts the remaining risk.
* The issues do not prevent safe implementation.

---

### FAIL

The project must not proceed to BUILD.

The project returns to:

**Phase 2 — DESIGN**

or, when the problem originates from unclear or incorrect requirements:

**Phase 1 — THINK**

---

## 5. Gate Decision Record

Record the decision:

**Gate Status:** PASS / CONDITIONAL PASS / FAIL

**Date:**

**Reviewer:**

**Outstanding Issues:**

**Required Actions:**

**Accepted Risks:**

**Notes:**

---

## 6. Re-entry

A failed Gate 2 does not terminate the project.

The project returns to the appropriate phase or activity required to resolve the identified issue.

After the issue is resolved, Gate 2 must be reviewed again.

---

## 7. Exit

Gate 2 is complete when the gate decision has been recorded.

If approved:

**DESIGN → GATE 2 → BUILD**

The approved DESIGN package becomes the:

**DESIGN BASELINE**

BUILD is expected to implement the approved design unless a controlled change requires the project to return to DESIGN.
