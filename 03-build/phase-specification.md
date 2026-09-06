# Phase 3 — BUILD

## 1. Purpose

BUILD transforms the approved DESIGN BASELINE into a working implementation.

The purpose of this phase is to implement the approved solution according to the architecture, technical design, UX, integrations, security requirements, and implementation plan established during DESIGN.

BUILD is responsible for creating, configuring, integrating, and modifying the actual system.

BUILD implements:

**THE APPROVED HOW**

It does not independently redefine the project's requirements or architecture.

---

## 2. Inputs

BUILD receives the complete DESIGN Handoff Package:

* Architecture
* Technical Design
* UX Design, when applicable
* Data Design, when applicable
* Integration Design, when applicable
* Security Design
* Technology Decisions
* Implementation Plan
* Design Risks
* Requirements Traceability

BUILD may also receive:

* Existing source code
* Existing website or application
* Existing database
* Existing infrastructure
* APIs and credentials through approved secure mechanisms
* Design assets
* Configuration files
* Development environment
* External service documentation
* Test data
* Project-specific standards

The DESIGN BASELINE is the primary implementation reference.

---

## 3. Process

### Step 1 — Review BUILD Handoff

Review the complete DESIGN Handoff Package before implementation begins.

Confirm:

* What is being built
* Why it is being built
* How it is designed
* What technologies are required
* What integrations are required
* What security requirements apply
* What implementation sequence is expected

---

### Step 2 — Prepare the Build Environment

Prepare the required development environment.

This may include:

* Repository
* Local development environment
* Dependencies
* Frameworks
* Development tools
* Environment variables
* Configuration
* Databases
* APIs
* Development services

Secrets and credentials must never be hard-coded into source code or committed to the repository.

---

### Step 3 — Establish the Implementation Structure

Set up the project structure according to the approved design.

This may include:

* Application structure
* Components
* Modules
* Services
* Database structure
* Configuration
* Assets
* Testing structure
* Documentation structure

---

### Step 4 — Implement Core Functionality

Implement the system according to the approved requirements and design.

Implementation may include:

* Frontend
* Backend
* Database
* Business logic
* APIs
* Integrations
* Automations
* Authentication
* Authorization
* Forms
* Workflows
* Data processing
* Error handling

Implementation should follow the planned task sequence whenever practical.

---

### Step 5 — Implement User Experience

When applicable, implement:

* Pages
* Screens
* Navigation
* Components
* Forms
* Interactions
* Responsive behavior
* Loading states
* Empty states
* Error states
* Success states

Implementation should remain aligned with the approved UX design.

---

### Step 6 — Implement Security Controls

Implement the security controls defined during DESIGN.

This may include:

* Authentication
* Authorization
* Input validation
* Data protection
* Access control
* Secure API handling
* Secrets management
* Session management
* Security configuration

Security must be considered throughout BUILD rather than postponed until the end.

---

### Step 7 — Implement Integrations

Configure and implement approved integrations.

Examples include:

* APIs
* Payment systems
* Email services
* Calendar systems
* Webhooks
* CRM systems
* Automation platforms
* AI services
* External databases

Integration behavior should follow the approved Integration Design.

---

### Step 8 — Test During Implementation

Perform testing continuously during BUILD.

Testing may include:

* Unit testing
* Component testing
* Integration testing
* Manual functional testing
* API testing
* Data validation
* Error-path testing

BUILD testing does not replace the formal validation performed in Phase 4.

---

### Step 9 — Review Implementation Against Design

Compare the implementation against the DESIGN BASELINE.

Verify:

* Architecture was followed.
* Major components match the design.
* Requirements are being implemented.
* Integrations match the approved design.
* Security controls are implemented.
* UX remains aligned with the approved design.

---

### Step 10 — Manage Deviations

If implementation requires a change from the approved design:

1. Identify the deviation.
2. Determine why it is necessary.
3. Assess its impact.
4. Document the change.
5. Determine whether DESIGN review is required.

BUILD must not silently introduce major architectural changes.

If the deviation changes the architecture, major technology decisions, system behavior, or important requirements, the project should return to DESIGN for controlled revision.

---

### Step 11 — Resolve Build Issues

Identify and resolve:

* Implementation errors
* Dependency problems
* Integration failures
* Configuration issues
* Data issues
* Security issues
* Performance problems
* Unexpected system behavior

Issues that cannot be safely resolved within BUILD should be escalated to the appropriate earlier phase.

---

### Step 12 — Prepare the VALIDATE Handoff

When implementation is complete, prepare the system and artifacts required for formal validation.

The implementation must be in a state where Phase 4 can verify whether the solution actually satisfies the approved requirements.

---

## 4. Recommended AI / Tools

### Primary AI — Codex or Claude

Role:

**Software Engineer / Implementation Agent**

AI may assist with:

* Writing code
* Modifying code
* Refactoring
* Debugging
* Creating tests
* Implementing integrations
* Reviewing implementation
* Explaining technical issues
* Following the approved architecture
* Identifying implementation problems

### Tool Selection

The framework does not require a specific coding AI.

Possible implementation tools include:

* Codex
* Claude
* Other capable coding agents
* Human developers
* Development environments
* Testing tools
* Version control tools

The tool is replaceable.

The framework remains responsible for controlling the process.

### Human Oversight

AI-generated implementation must not automatically be considered correct.

Important implementation decisions, security-sensitive changes, architectural deviations, and production-impacting changes require appropriate human review.

---

## 5. Required Outputs / Artifacts

BUILD should produce the following when applicable:

* Working source code
* Configured application/system
* Database implementation
* Implemented integrations
* Implemented automations
* Tests
* Configuration documentation
* Build notes
* Known issues
* Deviation/change records
* Updated requirements traceability
* Validation-ready implementation

The exact artifacts depend on project type.

---

## 6. Completion Criteria

BUILD is complete only when:

* [ ] Approved requirements have been implemented.
* [ ] Approved architecture has been implemented.
* [ ] Major components are implemented.
* [ ] Required integrations are implemented.
* [ ] Required security controls are implemented.
* [ ] User experience is implemented when applicable.
* [ ] Core functionality works.
* [ ] Build-level tests have been performed.
* [ ] Known implementation issues are documented.
* [ ] Design deviations are documented.
* [ ] Major undocumented architectural changes do not remain.
* [ ] The implementation is ready for formal validation.
* [ ] Required BUILD artifacts are prepared.
* [ ] The VALIDATE handoff package is complete.

A conversation with an AI or generated code alone does not constitute completion.

Completion is determined by the implementation and the required evidence.

---

## 7. Handoff Requirements → Phase 4

Phase 4 — VALIDATE must receive:

1. Working implementation
2. Implemented features
3. Tests and test results, when applicable
4. Build notes
5. Known issues
6. Deviation/change records
7. Updated requirements traceability
8. Required configuration or test instructions
9. Any information necessary to reproduce and evaluate the system

The VALIDATE phase must be able to determine:

* What was implemented
* What requirements were addressed
* How the implementation should be tested
* What known limitations exist
* What deviations occurred
* What evidence already exists

VALIDATE should not need to reconstruct implementation history from AI conversations.

---

## Build Baseline

When BUILD reaches a validation-ready state, the resulting implementation becomes the:

**BUILD CANDIDATE**

The BUILD CANDIDATE is the implementation submitted to Phase 4 for formal validation.

BUILD is not considered successful merely because the system runs.

The implementation must be evaluated against the approved requirements and design during VALIDATE.

---

## Phase Boundary

BUILD implements:

**THE APPROVED HOW**

VALIDATE determines:

**WHETHER IT ACTUALLY WORKS AND SATISFIES THE REQUIREMENTS**

BUILD should not approve its own final success.

Formal acceptance belongs to Phase 4 — VALIDATE.

---

## Phase Exit

BUILD may proceed to Gate 3 only when all required BUILD completion criteria are satisfied.

**BUILD → GATE 3 → VALIDATE**
