# Phase 5 — DOCUMENT

## 1. Purpose

DOCUMENT transforms the validated system and its accumulated project knowledge into clear, usable, and maintainable documentation.

The purpose of this phase is to ensure that people can understand, operate, maintain, troubleshoot, and hand off the system without depending on the original AI conversations.

DOCUMENT preserves:

**UNDERSTANDING AND OPERATIONAL KNOWLEDGE**

It does not replace source-code preservation or version control.

Those responsibilities belong to Phase 6 — PRESERVE.

---

## 2. Inputs

DOCUMENT receives:

* Validated Release Candidate
* Validation results
* Acceptance decision
* Requirements
* Design Baseline
* Architecture
* Technical Design
* UX Design, when applicable
* Integration Design, when applicable
* Security Design
* Technology Decisions
* Build notes
* Known limitations
* Known issues
* Configuration information
* Operational procedures

DOCUMENT may also receive:

* Source code
* Repository structure
* Deployment information
* Environment information
* API documentation
* User instructions
* Troubleshooting information
* Maintenance procedures
* Business process information

---

## 3. Process

### Step 1 — Identify Documentation Requirements

Determine what documentation is required based on:

* Project complexity
* Users
* Operators
* Developers
* Administrators
* Maintainers
* Business stakeholders
* Security requirements
* Operational needs

Not every project requires every type of documentation.

---

### Step 2 — Document the System Overview

Create a clear explanation of:

* What the system does
* Why it exists
* Who uses it
* Major capabilities
* Major components
* Important dependencies

The documentation should allow a new person to understand the system without reading the entire source code.

---

### Step 3 — Document Architecture and Technical Structure

When applicable, document:

* Architecture
* Components
* Data flow
* System boundaries
* Dependencies
* Technologies
* Integrations
* Important technical decisions

Documentation should reflect the validated implementation rather than an outdated design.

---

### Step 4 — Document User Operations

When applicable, document:

* How users access the system
* How to perform important tasks
* Common workflows
* Inputs
* Outputs
* Expected behavior
* Common errors
* User-facing limitations

---

### Step 5 — Document Administration and Maintenance

When applicable, document:

* Configuration
* Environment variables
* Deployment
* Updates
* Maintenance procedures
* Backup procedures
* Recovery procedures
* Monitoring
* Troubleshooting
* Dependency management

Secrets and credentials must not be stored directly in documentation.

---

### Step 6 — Document Integrations

When applicable, document:

* Connected systems
* APIs
* Authentication methods
* Data exchanged
* Trigger conditions
* Webhooks
* Failure behavior
* Important configuration

Sensitive credentials must never be documented in plain text.

---

### Step 7 — Document Security Considerations

When applicable, document:

* Authentication model
* Authorization model
* Access levels
* Sensitive data handling
* Security controls
* Security responsibilities
* Security-related operational procedures

Documentation should explain how the system is expected to be operated securely.

---

### Step 8 — Document Known Limitations

Record:

* Known limitations
* Accepted defects
* Unsupported scenarios
* Technical constraints
* Performance limitations
* Future considerations

Documentation must not present known limitations as completed functionality.

---

### Step 9 — Document Important Decisions

Record important decisions made throughout the project.

When useful, document:

* Decision
* Context
* Options considered
* Selected approach
* Reason
* Consequences

This prevents future maintainers from having to rediscover why important choices were made.

---

### Step 10 — Review Documentation Against the Final System

Verify that documentation matches the validated implementation.

Remove or update:

* Outdated instructions
* Incorrect architecture
* Obsolete configurations
* Superseded decisions
* References to features that do not exist

Documentation must describe the actual accepted system.

---

### Step 11 — Prepare the PRESERVE Handoff

Prepare the final documentation package and identify the project artifacts that must be preserved in Phase 6.

---

## 4. Recommended AI / Tools

### Primary AI — ChatGPT

Role:

**Technical Writer / Knowledge Organizer**

AI may assist with:

* Organizing documentation
* Explaining technical concepts
* Converting technical information into user-friendly instructions
* Creating documentation structures
* Summarizing validated system behavior
* Identifying documentation gaps
* Reviewing consistency
* Creating troubleshooting guides
* Creating maintenance documentation

Other capable AI tools may also be used.

The framework remains tool-agnostic.

### Human Review

Documentation should be reviewed by an appropriate human when accuracy is important.

AI must not invent:

* System behavior
* Configuration
* Credentials
* Procedures
* Architecture
* Features
* Operational requirements

Unknown information must be clearly marked for confirmation.

---

## 5. Required Outputs / Artifacts

Documentation should include applicable artifacts such as:

* README
* System Overview
* User Guide
* Architecture Documentation
* Technical Documentation
* Configuration Guide
* Deployment Guide
* Operations Guide
* Maintenance Guide
* Troubleshooting Guide
* Integration Documentation
* Security Documentation
* Decision Records
* Known Limitations
* Change Information

Not every project requires every artifact.

Documentation should be proportional to project complexity and operational needs.

---

## 6. Completion Criteria

DOCUMENT is complete only when:

* [ ] System purpose is documented.
* [ ] Major functionality is documented.
* [ ] Relevant architecture is documented.
* [ ] Relevant technical structure is documented.
* [ ] User procedures are documented when applicable.
* [ ] Administration procedures are documented when applicable.
* [ ] Maintenance procedures are documented when applicable.
* [ ] Deployment information is documented when applicable.
* [ ] Integrations are documented when applicable.
* [ ] Security considerations are documented when applicable.
* [ ] Known limitations are documented.
* [ ] Important decisions are recorded.
* [ ] Documentation matches the validated implementation.
* [ ] Outdated or conflicting documentation has been removed or corrected.
* [ ] Documentation does not contain secrets or credentials.
* [ ] PRESERVE has sufficient information to preserve the project correctly.

A collection of AI-generated documents does not constitute completion.

Documentation is complete only when it accurately represents the accepted system and provides useful operational knowledge.

---

## 7. Handoff Requirements → Phase 6

Phase 6 — PRESERVE must receive:

1. Final documentation
2. Validated Release Candidate
3. Source code
4. Project configuration
5. Relevant project artifacts
6. Final architecture and technical information
7. Important decision records
8. Known limitations
9. Deployment information
10. Required recovery information
11. Version and release information

PRESERVE must be able to establish a durable and recoverable project state.

---

## Documentation Baseline

When documentation is completed, the resulting documentation package becomes the:

**DOCUMENTATION BASELINE**

The DOCUMENTATION BASELINE represents the accepted understanding of the system at the time of handoff.

Future changes should update documentation when the system behavior or operational requirements change.

---

## Phase Boundary

DOCUMENT preserves:

**UNDERSTANDING**

PRESERVE preserves:

**THE ACTUAL PROJECT STATE**

DOCUMENT does not replace:

* Source control
* Version history
* Backups
* Release management
* Artifact preservation

Those responsibilities belong to Phase 6 — PRESERVE.

---

## Phase Exit

DOCUMENT may proceed to Gate 5 only when all required documentation criteria are satisfied.

**DOCUMENT → GATE 5 → PRESERVE**
