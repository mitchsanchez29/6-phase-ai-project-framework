# Phase 6 — PRESERVE

## 1. Purpose

PRESERVE establishes the final durable, versioned, recoverable state of the completed project.

The purpose of this phase is to ensure that the accepted system, source code, documentation, configuration, decisions, and relevant project artifacts remain available for future use, maintenance, recovery, auditing, and further development.

PRESERVE establishes:

**THE DURABLE SOURCE OF TRUTH**

GitHub is the recommended preservation platform for source-controlled projects.

However, PRESERVE is a framework responsibility, not a requirement to use a specific platform.

Other appropriate version-control or storage systems may be used when required.

---

## 2. Inputs

PRESERVE receives:

* Validated Release Candidate
* Documentation Baseline
* Source code
* Project configuration
* Project documentation
* Architecture
* Technical information
* Decision records
* Known limitations
* Deployment information
* Recovery information
* Version information
* Relevant project artifacts
* Gate decisions
* Acceptance records

---

## 3. Process

### Step 1 — Review Final Project State

Confirm the project state being preserved.

Verify:

* Correct project
* Correct version
* Accepted implementation
* Final documentation
* Required configuration
* Required project artifacts

The preserved state must correspond to the accepted project state.

---

### Step 2 — Organize the Repository

Ensure the repository has a logical and maintainable structure.

The repository should make it clear where appropriate:

* Source code
* Documentation
* Configuration
* Tests
* Assets
* Architecture
* Decisions
* Project standards
* Templates
* Release information

Repository organization should reflect project needs.

---

### Step 3 — Review Version Control

Ensure important project changes are represented through version control.

Review:

* Commit history
* Branches
* Tags
* Releases
* Change history
* Important milestones

Version control should make it possible to understand how the project evolved.

---

### Step 4 — Preserve the Accepted Version

Identify the version that represents the accepted project state.

When appropriate:

* Create a version tag.
* Create a release.
* Record the release date.
* Record the release identifier.
* Record important release notes.

The goal is to create an identifiable recovery point.

---

### Step 5 — Preserve Documentation

Ensure the final documentation is stored with the appropriate project artifacts.

This may include:

* README
* User documentation
* Technical documentation
* Architecture
* Deployment instructions
* Maintenance instructions
* Troubleshooting
* Security documentation
* Decision records
* Known limitations

Documentation must correspond to the preserved version.

---

### Step 6 — Preserve Configuration

Preserve the configuration required to understand and reproduce the system.

This may include:

* Configuration structure
* Environment variable names
* Dependency definitions
* Build configuration
* Deployment configuration
* Infrastructure configuration

Secrets and credentials must not be committed.

When sensitive configuration is required, document the secure method for supplying it rather than storing the secret itself.

---

### Step 7 — Verify Recoverability

Determine whether the project can be recovered from the preserved state.

Verify, when applicable:

* Repository can be accessed.
* Source code is complete.
* Required files are present.
* Dependencies are identifiable.
* Configuration requirements are documented.
* Documentation is available.
* Release/version can be identified.
* Recovery or deployment process is documented.

The goal is not merely storage.

The goal is:

**STORAGE + IDENTIFIABILITY + RECOVERABILITY**

---

### Step 8 — Verify Preservation Integrity

Check that the preserved project state is consistent.

Verify:

* Documentation matches the preserved version.
* Source matches the identified release.
* Required artifacts are present.
* No critical files are missing.
* No unintended secrets are present.
* Important decisions are preserved.
* Release information is accurate.

---

### Step 9 — Record Final Project State

Record important final information such as:

* Project version
* Release identifier
* Preservation date
* Repository location
* Deployment state
* Known limitations
* Accepted risks
* Maintenance status
* Next planned action, when applicable

---

### Step 10 — Establish Maintenance Ownership

When applicable, identify:

* Responsible person
* Maintenance owner
* Repository owner
* Deployment responsibility
* Access responsibility
* Support responsibility

The project should have a clear understanding of who is responsible for future changes.

---

### Step 11 — Prepare Future Change Management

The preserved project becomes the starting point for future changes.

Future work should not modify the preserved baseline without appropriate version control.

A future change may begin a new lifecycle iteration:

**THINK → DESIGN → BUILD → VALIDATE → DOCUMENT → PRESERVE**

The framework is therefore iterative rather than permanently ending after one cycle.

---

## 4. Recommended AI / Tools

### Primary Platform — GitHub

Role:

**Version Control / Source Preservation / Collaboration**

GitHub may be used for:

* Source control
* Commit history
* Branches
* Pull requests
* Releases
* Tags
* Documentation
* Project artifacts
* Change history

### AI Assistance

AI may assist with:

* Repository organization
* Release notes
* Documentation review
* Change summaries
* Repository audits
* Identifying missing artifacts
* Reviewing configuration
* Creating maintenance checklists

AI does not replace version control or preservation mechanisms.

---

## 5. Required Outputs / Artifacts

PRESERVE should produce or confirm, when applicable:

* Version-controlled source
* Final repository state
* Release or version identifier
* Release notes
* Final documentation
* Configuration information
* Decision records
* Change history
* Recovery information
* Maintenance ownership
* Preservation record

The exact artifacts depend on project type.

---

## 6. Completion Criteria

PRESERVE is complete only when:

* [ ] Accepted project state is identified.
* [ ] Source code is preserved.
* [ ] Required project artifacts are preserved.
* [ ] Final documentation is preserved.
* [ ] Important decisions are preserved.
* [ ] Configuration requirements are preserved.
* [ ] Secrets and credentials are not improperly stored.
* [ ] Version information is recorded.
* [ ] Release or recovery point is identifiable.
* [ ] Repository structure is understandable.
* [ ] Change history is available.
* [ ] Recoverability has been considered or verified.
* [ ] Maintenance ownership is identified when applicable.
* [ ] Final project state is recorded.

Simply uploading files does not constitute preservation.

Preservation requires an identifiable, versioned, understandable, and recoverable project state.

---

## 7. Final Framework State

When PRESERVE is successfully completed, the project has reached a durable lifecycle state.

The preserved project should contain sufficient information to support:

* Future maintenance
* Future development
* Troubleshooting
* Recovery
* Handoff
* Auditing
* Reuse
* New lifecycle iterations

The preserved state becomes the starting point for future project changes.

---

## 8. Iteration Principle

The framework does not permanently end after PRESERVE.

When a new requirement, improvement, defect, or change is identified, a new lifecycle iteration may begin.

The project may return to the appropriate phase based on the nature of the change.

Examples:

**New requirement → THINK**

**Architecture change → DESIGN**

**Implementation change → BUILD**

**Verification → VALIDATE**

**Documentation update → DOCUMENT**

**Version/release preservation → PRESERVE**

The lifecycle therefore operates as a controlled continuous improvement loop.

---

## 9. Phase Boundary

DOCUMENT preserves:

**UNDERSTANDING**

PRESERVE preserves:

**THE DURABLE PROJECT STATE**

PRESERVE does not replace:

* Validation
* Acceptance
* Documentation
* Security review
* Change management

It preserves the result of those activities in a durable form.

---

## Phase Exit

PRESERVE is complete when the final project state satisfies the preservation completion criteria.

The complete lifecycle is:

**THINK → GATE 1 → DESIGN → GATE 2 → BUILD → GATE 3 → VALIDATE → GATE 4 → DOCUMENT → GATE 5 → PRESERVE**

After preservation, future changes may initiate another controlled lifecycle iteration.
