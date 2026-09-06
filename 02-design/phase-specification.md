# Phase 2 — DESIGN

## 1. Purpose

DESIGN transforms the approved project definition from Phase 1 — THINK into a complete, build-ready solution design.

The purpose of this phase is to determine how the approved requirements will be implemented.

DESIGN defines the solution architecture, user experience, technical structure, technology choices, integrations, security considerations, and implementation strategy required for BUILD.

DESIGN defines HOW.

It does not implement the production solution. Implementation belongs to Phase 3 — BUILD.

---

## 2. Inputs

DESIGN receives the complete THINK Handoff Package:

* Project Brief
* Requirements
* Scope
* Success Criteria
* Assumptions
* Decisions
* Risks
* Open Questions

DESIGN may also receive:

* Existing code
* Existing system architecture
* Existing website or application
* Existing documentation
* Brand and design assets
* Database information
* API documentation
* Platform requirements
* Infrastructure information
* Existing integrations

If DESIGN discovers that a requirement is fundamentally unclear, contradictory, or incorrect, the issue should be returned to Phase 1 — THINK rather than silently inventing a requirement.

---

## 3. Process

### Step 1 — Review Requirements

Review the approved THINK artifacts and confirm that the intended solution addresses the project requirements.

### Step 2 — Analyze Constraints

Determine how requirements interact with:

* Budget
* Timeline
* Platform
* Technology
* Existing infrastructure
* Resources
* Scalability
* Security
* Operational limitations

### Step 3 — Define the Solution Approach

Establish the overall approach that will be used to solve the defined problem.

The solution approach must remain aligned with the approved requirements and scope.

### Step 4 — Design Architecture

Define, when applicable:

* System components
* Component responsibilities
* System boundaries
* Component relationships
* Data flow
* Dependencies
* External services
* Major architectural patterns

### Step 5 — Design User Experience

When applicable, define:

* User journeys
* User flows
* Navigation
* Page or screen structure
* Interactions
* System states
* Error states
* Important user experience requirements

### Step 6 — Design Data and System Structure

When applicable, define:

* Data entities
* Data models
* Database structure
* Schemas
* Relationships
* Storage
* State management
* Data flow

### Step 7 — Design Integrations

When applicable, define:

* APIs
* External services
* Authentication
* Webhooks
* Payment systems
* Email services
* Calendar systems
* Automation platforms
* Other third-party integrations

### Step 8 — Address Security and Reliability

Consider:

* Authentication
* Authorization
* Sensitive data
* Secrets management
* Input validation
* Error handling
* Failure recovery
* Backups
* Reliability
* Appropriate security controls

### Step 9 — Select Technologies

Select technologies based on:

* Project requirements
* Constraints
* Maintainability
* Reliability
* Security
* Scalability
* Available resources
* Existing infrastructure

Technology choices must not be based solely on AI preference.

### Step 10 — Create the Implementation Plan

Break the approved design into logical implementation units.

The implementation plan should provide BUILD with a clear sequence of work.

### Step 11 — Identify Design Risks

Document architectural, technical, integration, security, and implementation risks.

### Step 12 — Review Design Against Requirements

Perform a requirements-to-design traceability review.

Each important requirement should have a corresponding design solution or explicit explanation.

### Step 13 — Prepare the BUILD Handoff

Organize the completed design artifacts into a standardized handoff package.

---

## 4. Recommended AI / Tools

### Primary AI — Claude

Role:

**Solution Architect / Technical Designer**

Claude may assist with:

* Architecture
* Technical design
* User flows
* Data modeling
* Technology evaluation
* Integration planning
* Security considerations
* Implementation planning
* Design review
* Identifying design conflicts

### Tool-Agnostic Principle

The framework is independent of any specific AI provider.

Claude is the recommended primary worker for this phase, but another capable AI or tool may be used when appropriate.

AI recommendations do not automatically become project decisions.

Important technical and architectural decisions must be reviewed and accepted by the responsible human.

---

## 5. Required Outputs / Artifacts

DESIGN should produce the following artifacts when applicable:

* Architecture
* Technical Design
* UX Design
* Data Design
* Integration Design
* Security Design
* Technology Decisions
* Implementation Plan
* Design Risks
* Requirements Traceability

The complete set forms the DESIGN Handoff Package.

Not every project requires every artifact.

Artifacts should be created according to the complexity and needs of the project.

---

## 6. Completion Criteria

DESIGN is complete only when:

* [ ] All approved requirements have been considered.
* [ ] The overall solution approach is defined.
* [ ] Architecture is documented when applicable.
* [ ] Major components are defined.
* [ ] Component responsibilities are clear.
* [ ] User flows are defined when applicable.
* [ ] Data structure is defined when applicable.
* [ ] Integrations are defined when applicable.
* [ ] Technology choices are documented.
* [ ] Security considerations are addressed.
* [ ] Reliability and failure handling are considered.
* [ ] Major design decisions are recorded.
* [ ] Design risks are documented.
* [ ] The implementation can be divided into buildable tasks.
* [ ] Requirements can be traced to design decisions.
* [ ] No critical architectural ambiguity remains.
* [ ] BUILD can begin without making major undocumented design decisions.

A conversation with an AI does not constitute completion.

Completion is determined by the required artifacts and completion criteria.

---

## 7. Handoff Requirements → Phase 3

Phase 3 — BUILD must receive the complete DESIGN Handoff Package:

1. Architecture
2. Technical Design
3. UX Design, when applicable
4. Data Design, when applicable
5. Integration Design, when applicable
6. Security Design
7. Technology Decisions
8. Implementation Plan
9. Design Risks
10. Requirements Traceability

The handoff must allow BUILD to understand:

* What is being built
* How the solution is structured
* What technologies are being used
* How major components interact
* What integrations are required
* What security considerations apply
* What implementation sequence should be followed
* What requirements each part of the design addresses

BUILD should not need to reconstruct the design from the original AI conversation.

---

## Design Baseline

At the completion of DESIGN, the approved solution becomes the:

**DESIGN BASELINE**

The DESIGN BASELINE represents the approved solution that Phase 3 — BUILD is expected to implement.

Changes to major architectural or technical decisions during BUILD should be reviewed and, when necessary, returned to DESIGN for controlled revision.

---

## Phase Boundary

DESIGN defines:

**HOW**

BUILD implements:

**THE APPROVED HOW**

DESIGN does not implement production code or the final working system.

If implementation reveals that the approved architecture is inadequate, the project should return to DESIGN for review rather than allowing major architectural changes to occur without documentation.

---

## Phase Exit

DESIGN may proceed to Gate 2 only when all required completion criteria are satisfied.

**DESIGN → GATE 2 → BUILD**
