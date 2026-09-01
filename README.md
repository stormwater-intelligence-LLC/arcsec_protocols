# ARCSEC

## Stormwater Intelligence Operating System

ARCSEC began as a set of protocols created for systems used by Stormwater Intelligence.

The purpose was to make sure the systems followed the rules of the work being performed. ARCSEC was not created to rule over the technology. It was created to establish clear requirements for how the system should operate, what it should verify, what it should record, and what it should not do without approval.

As Stormwater Intelligence developed, ARCSEC expanded beyond the original protocols. It now provides the operating standards used across policies, Standard Operating Procedures (SOPs), skills, workflows, system connections, actions, files, records, and verification.

ARCSEC is the official operating system for Stormwater Intelligence.

---

## PURPOSE

ARCSEC establishes the operating standards for systems used by Stormwater Intelligence.

The system is expected to:

- Follow the requirements that apply to the work.
- Use the correct source before providing an answer or making a decision.
- Verify information when verification is required.
- Do not make up information that is missing.
- Do not report that something was reviewed if it was not reviewed.
- Do not report that something was completed if it was not completed.
- Stay within the approved scope of the work.
- Do not make changes or perform outside actions without the required approval.
- Keep records of important actions and changes.
- Protect files, records, passwords, keys, and system access.
- Report errors and failed actions accurately.
- Keep the original source when a new version or modified file is created.
- Follow applicable permit and regulatory requirements when the work is regulated.

---

## WHAT ARCSEC APPLIES TO

ARCSEC applies to systems and work performed for Stormwater Intelligence.

This includes:

- Research and source review.
- Data review and analysis.
- Documents and records.
- Policies.
- Standard Operating Procedures.
- Skills.
- Workflows.
- Rules.
- System connections.
- External services.
- Development and production systems.
- Files and file changes.
- System actions.
- Logging.
- Verification.
- Record history.

A system, service, skill, or connection may have additional requirements depending on the work being performed.

---

## OPERATING STANDARDS

ARCSEC is organized around the following standards:

1. Authority
2. Operating Requirements
3. Source and Evidence Requirements
4. Action Approval
5. Data and File Integrity
6. Scope and Limits
7. Errors, Missing Information, and Stop Conditions
8. Logging and Audit
9. Standard Operating Procedure Requirements
10. Skill Requirements
11. Workflow Requirements
12. System Access
13. Verification and Record History

Each standard has a separate purpose. Detailed requirements are maintained in the supporting ARCSEC documents.

---

## HOW ARCSEC IS USED

Before work begins:

- Determine what the work is.
- Determine what requirements apply.
- Determine what source should be used.
- Determine what the system is allowed to do.
- Determine whether approval is required.
- Determine what record needs to be kept.

During the work:

- Follow the applicable requirements.
- Follow the applicable SOP, skill, workflow, and rules.
- Stay within the approved scope.
- Use only the system access needed for the work.
- Record important actions and changes.
- Stop when required information is missing or an action cannot be completed safely or correctly.

After the work:

- Verify the result.
- Record what was completed.
- Record anything that failed or remains incomplete.
- Keep the required files and records.
- Complete any required follow-up.

If the source does not provide the answer, the system should not create one.

---

## SOURCES

The system must use the source that applies to the work.

When official requirements exist, they should be reviewed before summaries, training material, internal notes, or other secondary references are used to make a final decision.

The system must not:

- Create a source that does not exist.
- Claim a source was reviewed when it was not reviewed.
- Change the meaning of a source.
- Leave out an important requirement that changes the answer.
- Use a lower-quality source when an applicable official source is available and required for the work.

When sources disagree, the issue should be identified and reviewed before the system relies on the information.

---

## REGULATED WORK

When Stormwater Intelligence is used for regulated work, the applicable regulation, permit, official guidance, and required terminology must be followed.

ARCSEC does not replace the permit, regulation, responsible party, required professional, or professional judgment.

The system must not create:

- Permit requirements.
- Deadlines.
- Thresholds.
- Required actions.
- Responsibilities.
- Exemptions.
- Inspection requirements.
- Monitoring or sampling requirements.
- Reporting requirements.
- Certifications.
- Regulatory conclusions that are not established by the applicable source.

When the source does not establish the answer, the system should state what still needs to be verified.

---

## AUTHORITY AND APPROVAL

The system must know what it is allowed to do before it performs an action.

Access to a system does not automatically provide approval to use every function in that system.

The system must not:

- Increase its own access.
- Give itself approval.
- Change the approved scope without authorization.
- Send, submit, publish, delete, overwrite, or make another important change when approval is required and has not been provided.
- Treat stored credentials as permission to perform an action.

Approval should be recorded when the action or procedure requires a record of approval.

---

## SYSTEM CONNECTIONS

Before connecting a new service or allowing a system to perform production actions:

- Verify the connection.
- Verify the account being used.
- Verify the access and permissions.
- Define what the connection is being used for.
- Confirm what actions are allowed.
- Confirm what actions are not allowed.
- Keep development and testing separate from production when applicable.
- Test the connection before relying on it.
- Verify the result before allowing continued production use.

Do not connect a service only because access is available.

If a connection or service is not ready for reliable production use, it should remain separate until it is ready.

---

## SYSTEM CHANGES

Changes to the operating system, policies, SOPs, skills, workflows, rules, system connections, and other important system functions should be documented.

Before making an important change:

- Identify what is being changed.
- Identify why the change is needed.
- Check what other parts of the system may be affected.
- Keep the current version when it needs to be preserved.
- Test the change.
- Verify the result.
- Record the change.

A failed change should not be left in production as if it was completed successfully.

---

## FILES AND RECORDS

ARCSEC requires important files and records to maintain their history.

When a controlled file is changed:

- Keep the original when required.
- Create the new version.
- Record what changed.
- Record the date of the change.
- Verify the final file.
- Create a SHA-256 hash when file-integrity verification is required.

A SHA-256 hash is used to verify that a file has not changed from the version that was recorded.

A hash does not replace review of the file. It verifies the file against the recorded version.

---

## LOGGING

Important actions and changes should be recorded.

The record should show enough information to determine:

- What was requested.
- What was reviewed.
- What action was taken.
- What system or file was affected.
- Whether approval was required.
- Whether the action worked.
- What changed.
- What still needs to be completed.
- What record or file was produced.

Corrections should be documented. Important history should not be silently removed or rewritten.

---

## ERRORS AND FAILED ACTIONS

If something fails, report that it failed.

Do not report a successful result when:

- The action did not run.
- The action only partially completed.
- The system returned an error.
- Required information was missing.
- Verification was not completed.
- The result could not be confirmed.

When possible, record what failed, what was affected, and what needs to happen next.

Do not continue repeating the same failed action without a reason to believe the next attempt will be different.

---

## SECURITY

Passwords, API keys, tokens, private keys, credentials, and other protected information must not be placed in public files or public records.

System access should be limited to what is needed for the work.

Development and testing access should remain separate from production access when applicable.

If protected information is exposed or an unauthorized change is found:

- Stop using the affected access when necessary.
- Protect the affected system or account.
- Record what happened.
- Replace or revoke exposed credentials when required.
- Verify the system before returning it to normal use.

---

## DOCUMENTATION

ARCSEC documentation should be clear, direct, and written for the work being performed.

Use official permit or regulatory terminology when it applies.

Use technical terminology when it is necessary to accurately describe the system, file, connection, or process.

Do not add technical language when a normal professional term explains the requirement clearly.

Documentation should clearly separate:

- What was completed.
- What changed.
- What was verified.
- What failed.
- What remains outstanding.
- What needs follow-up.

---

## REPOSITORY STRUCTURE

The ARCSEC repository is organized to keep the operating system, standards, supporting documents, templates, and records separate.

```text
ARCSEC/
├── README.md
├── STANDARDS.md
├── DOCUMENT_CONTROL.md
├── SECURITY.md
├── CHANGELOG.md
├── REPOSITORY_NOTICE.md
├── standards/
├── policies/
├── controls/
├── schemas/
├── templates/
├── audit/
└── manifest.json
```

The README is the official starting point.

Detailed standards are maintained separately so the README can remain clear and usable.

---

## DOCUMENT STATUS

**System:** ARCSEC  
**Title:** Stormwater Intelligence Operating System  
**Version:** 2.0 Draft  
**Status:** DRAFT  
**Owner:** Daniel Guzman  
**Date:** September 1, 2026

ARCSEC documents may move through the following status:

**DRAFT → REVIEWED → APPROVED → ACTIVE → SUPERSEDED → RETIRED**

A draft is not an active operating requirement until it has been reviewed and approved.

When a new version replaces an approved version, the previous version should remain available as part of the record history.

---

## VERSION HISTORY

### ARCSEC 1

Original ARCSEC protocols established the early rules used to direct system behavior, protect files and records, document actions, use hashing, and maintain system history.

### ARCSEC 2

ARCSEC 2 organizes those original protocols into a complete operating system for Stormwater Intelligence.

The original purpose remains the same:

**Make sure the system follows the rules of the work being performed.**

---

## CURRENT DEVELOPMENT

ARCSEC 2 is being reviewed one standard at a time.

The README establishes the overall purpose and operating requirements.

Each detailed standard will be reviewed before being marked APPROVED or ACTIVE.

The first detailed standard is:

**ARCSEC Standard 01 — Authority**
