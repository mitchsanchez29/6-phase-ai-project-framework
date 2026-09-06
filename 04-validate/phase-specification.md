# Phase 4 — VALIDATE

## 1. Purpose

VALIDATE determines whether the implemented solution satisfies the approved requirements, design, quality expectations, security requirements, and acceptance criteria.

The purpose of this phase is to produce evidence that the system works as intended and is ready for acceptance, documentation, and preservation.

VALIDATE answers:

**DOES IT ACTUALLY WORK AND MEET THE REQUIREMENTS?**

Validation must not rely solely on an AI's opinion.

The validation process should use appropriate evidence such as:

* Automated tests
* Functional tests
* Integration tests
* Requirements checks
* Security checks
* User acceptance
* Manual inspection
* AI-assisted review
* Other project-appropriate verification methods

The level of validation should match the project's complexity, risk, and importance.

---

## 2. Inputs

VALIDATE receives:

* Requirements Baseline
* DESIGN BASELINE
* BUILD CANDIDATE
* Success Criteria
* Requirements Traceability
* Security requirements
* Test instructions
* Build notes
* Known issues
* Design deviations
* Test data, when applicable
* Acceptance criteria

VALIDATE may also receive:

* Source code
* Database
* APIs
* Deployment environment
* Configuration
* Existing system
* User accounts or test accounts
* External service environments

---

## 3. Process

### Step 1 — Review Validation Scope

Determine what must be validated based on:

* Requirements
* Success criteria
* Design
* Risk
* Project complexity
* Security requirements
* User expectations

Define the validation approach before testing begins.

---

### Step 2 — Create the Validation Plan

Define:

* What will be tested
* How it will be tested
* Expected results
* Required test data
* Required environments
* Acceptance criteria
* Responsible reviewer

The validation plan should provide traceability from requirements to evidence.

---

### Step 3 — Validate Requirements

Verify that the implementation satisfies the approved requirements.

For each important requirement, determine whether it is:

* PASS
* FAIL
* PARTIAL
* NOT APPLICABLE
* NOT TESTABLE

Evidence should be recorded where appropriate.

---

### Step 4 — Perform Functional Validation

Test the system's actual behavior.

This may include:

* User workflows
* Forms
* Calculations
* Business logic
* Navigation
* Data processing
* State changes
* Success conditions
* Error conditions
* Edge cases

Expected behavior must be compared with actual behavior.

---

### Step 5 — Perform Integration Validation

When applicable, verify:

* APIs
* Webhooks
* External services
* Payments
* Email
* Calendar
* CRM
* Automation systems
* AI services
* Data synchronization

Verify both successful and failure scenarios where appropriate.

---

### Step 6 — Perform Security Validation

When applicable, review:

* Authentication
* Authorization
* Access control
* Input validation
* Sensitive data handling
* Secrets exposure
* API security
* Session behavior
* Permissions
* Common security weaknesses

Security validation should be proportional to the project's risk.

---

### Step 7 — Perform Reliability and Error Validation

Verify how the system behaves when something goes wrong.

Test appropriate scenarios such as:

* Invalid input
* Missing data
* Failed API requests
* Network failures
* Service failures
* Unexpected states
* Duplicate actions
* Timeouts
* Recovery scenarios

The system should fail safely and provide appropriate behavior.

---

### Step 8 — Perform User Experience Validation

When applicable, verify:

* Usability
* Navigation
* Readability
* Responsiveness
* Accessibility
* Clear feedback
* Error messages
* Loading states
* Empty states
* Mobile behavior
* Desktop behavior

The implementation should match the approved UX requirements.

---

### Step 9 — Perform AI-Assisted Review

AI may be used to assist with:

* Code review
* Requirement comparison
* Test generation
* Edge-case identification
* Security review
* UX review
* Identifying inconsistencies
* Reviewing test results

AI review is supporting evidence.

It is not, by itself, final validation or acceptance.

AI must not be treated as an independent validator merely because a different AI model or provider was used.

---

### Step 10 — Record Defects

Every significant failure should be documented.

Record:

* Issue
* Expected behavior
* Actual behavior
* Severity
* Impact
* Reproduction steps
* Evidence
* Responsible action
* Resolution status

Defects should be classified according to project needs.

---

### Step 11 — Resolve Validation Failures

When validation fails:

1. Identify the root cause.
2. Determine the responsible phase.
3. Return the project to the appropriate phase.
4. Correct the issue.
5. Re-run the affected validation.

Possible return paths include:

**VALIDATE → BUILD**

when the problem is implementation-related.

**VALIDATE → DESIGN**

when the problem is caused by an inadequate design.

**VALIDATE → THINK**

when the requirement or intended outcome is incorrect, ambiguous, or incomplete.

---

### Step 12 — Confirm Acceptance Criteria

Review the final implementation against the approved success criteria and acceptance criteria.

Determine whether the system is:

* Accepted
* Conditionally Accepted
* Rejected

Acceptance must be based on documented evidence rather than assumption.

---

### Step 13 — Prepare the DOCUMENT Handoff

When validation is successful, prepare the information required for Phase 5 — DOCUMENT.

The handoff should include:

* Validation results
* Test results
* Accepted requirements
* Known limitations
* Remaining issues
* Final decisions
* Acceptance status
* Relevant operational information

---

## 4. Recommended AI / Tools

### AI Role

AI may act as:

**Validation Assistant / Reviewer / Test Engineer**

AI may assist with:

* Test planning
* Test case generation
* Requirement verification
* Code review
* Security review
* Edge-case analysis
* Test-result analysis
* Defect identification
* Regression analysis

Possible tools include:

* Claude
* ChatGPT
* Codex
* Automated testing frameworks
* Browser testing tools
* API testing tools
* Security testing tools
* Manual testing

The framework remains tool-agnostic.

---

## 5. Independent Validation Principle

Validation should provide meaningful independence from BUILD.

The AI or person that implemented the solution should not be the sole authority determining that the implementation is correct.

Where practical:

* Use a different reviewer.
* Use a different validation method.
* Use automated tests.
* Use human acceptance.
* Compare results against predefined criteria.

For higher-risk projects, stronger independent review should be used.

The goal is not to require a different AI provider.

The goal is to prevent:

**BUILD → "I built it, therefore it works."**

Instead:

**BUILD → evidence → VALIDATE → acceptance decision**

---

## 6. Required Outputs / Artifacts

VALIDATE should produce, when applicable:

* Validation Plan
* Test Cases
* Test Results
* Requirements Validation Matrix
* Defect Log
* Security Validation Results
* Integration Test Results
* User Acceptance Results
* Validation Summary
* Acceptance Decision
* Known Limitations
* Final Validation Evidence

The exact artifacts depend on project complexity and risk.

---

## 7. Completion Criteria

VALIDATE is complete only when:

* [ ] Validation scope is defined.
* [ ] Appropriate validation methods were selected.
* [ ] Approved requirements were evaluated.
* [ ] Success criteria were evaluated.
* [ ] Functional behavior was tested.
* [ ] Integrations were tested when applicable.
* [ ] Security was evaluated when applicable.
* [ ] Error and failure behavior was evaluated when applicable.
* [ ] User experience was evaluated when applicable.
* [ ] Significant defects are documented.
* [ ] Blocking defects are resolved or formally accepted.
* [ ] Validation evidence is recorded.
* [ ] Acceptance status is determined.
* [ ] Known limitations are documented.
* [ ] DOCUMENT has sufficient information to begin.
* [ ] No critical unresolved validation issue remains.

An AI statement such as "everything looks good" does not constitute validation.

Validation requires evidence.

---

## 8. Handoff Requirements → Phase 5

Phase 5 — DOCUMENT must receive:

1. Validation results
2. Test results
3. Requirements validation status
4. Acceptance decision
5. Known limitations
6. Remaining accepted issues
7. Important final decisions
8. Relevant operational information
9. Final system behavior
10. Required documentation inputs

DOCUMENT should not need to reconstruct the final system state from AI conversations.

---

## Validation Baseline

When validation is successfully completed, the accepted implementation becomes the:

**VALIDATED RELEASE CANDIDATE**

The VALIDATED RELEASE CANDIDATE represents the version that has passed the project's required validation and acceptance criteria.

---

## Phase Boundary

BUILD asks:

**DID WE IMPLEMENT THE DESIGN?**

VALIDATE asks:

**DOES THE IMPLEMENTATION ACTUALLY SATISFY THE REQUIREMENTS?**

DOCUMENT asks:

**CAN PEOPLE UNDERSTAND, OPERATE, MAINTAIN, AND HAND OFF THE SYSTEM?**

---

## Phase Exit

VALIDATE may proceed to Gate 4 only when all required validation criteria are satisfied.

**VALIDATE → GATE 4 → DOCUMENT**
