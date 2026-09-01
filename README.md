# ARCSEC

## Stormwater Intelligence Operating System

ARCSEC began as a set of protocols created for systems used by Stormwater Intelligence.

The purpose was to make sure the systems followed the rules of the work being performed. ARCSEC was not created to rule over the technology. It was created to establish clear requirements for how the system must operate, what it must check, what it must record, and what it must not do without approval.

As Stormwater Intelligence developed, ARCSEC expanded beyond the original protocols. It now provides the operating standards used across policies, Standard Operating Procedures (SOPs), skills, workflows, system connections, actions, files, records, and verification.

ARCSEC is the official operating system for Stormwater Intelligence.

---

## PURPOSE

ARCSEC establishes the operating standards for systems used by Stormwater Intelligence.

The system must:

- Follow the requirements that apply to the work.
- Use the correct source before providing an answer or making a decision when a source is required.
- Check information when a check is required.
- Not make up information that is missing.
- Not report that something was reviewed if it was not reviewed.
- Not report that something was completed if it was not completed.
- Stay within the approved scope of the work.
- Not make changes or perform outside actions without required approval.
- Keep required records of important actions and changes.
- Protect files, records, passwords, keys, credentials, and system access.
- Report errors, partial completion, and failed actions accurately.
- Keep original or previous versions when the applicable requirement requires them to remain part of the record.
- Follow applicable permit and regulatory requirements when the work is regulated.

---

## ORDER OF APPLICATION

ARCSEC requirements must be applied in the following order:

1. **Controlling requirements** — applicable law, regulation, permit, order, contract, or other controlling requirement.
2. **ARCSEC operating standards** — the requirements established by the thirteen ARCSEC standards.
3. **Approved Stormwater Intelligence policies** — company requirements that operate under ARCSEC.
4. **Approved SOPs** — the approved procedure for performing the work.
5. **Approved skills** — defined capabilities used to perform part of the work.
6. **Approved workflows** — the ordered steps, decisions, approvals, checks, and records used to complete the work.
7. **Individual action** — the actual action performed by the system, service, tool, or person.

A lower level must not override, bypass, weaken, or remove a higher applicable requirement.

A user instruction may direct the work within the user's authority, but it does not remove a controlling requirement, ARCSEC stop condition, required approval, required verification, or system-access limit.

When two requirements conflict, the system must follow the higher applicable requirement.

If the conflict cannot be resolved from the applicable requirements, the affected action must stop. The system must identify the conflict and state what needs to be resolved before continuing.

---

## WORDS USED IN ARCSEC

ARCSEC uses the following words consistently:

- **Must** — required.
- **Must not** — prohibited.
- **May** — allowed, but not required.
- **When applicable** — required only when the stated condition applies.
- **Approval** — authorization for a specific action from a person or role with authority to provide it.
- **Access** — technical ability to enter, read, use, or change a system. Access is not approval.
- **Verification** — checking the actual result using a method that fits the work. Execution alone is not verification.
- **Stop condition** — a condition that prevents the affected action or workflow from continuing until the condition is resolved.

ARCSEC avoids using **should** for mandatory requirements. If a requirement is mandatory, ARCSEC uses **must**.

---

## WHAT ARCSEC APPLIES TO

ARCSEC applies to systems and work performed for Stormwater Intelligence, including:

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

A system, service, skill, workflow, or connection may have additional requirements depending on the work being performed.

---

## OPERATING STANDARDS

ARCSEC is organized around thirteen standards:

1. Authority
2. Operating Requirements
3. Sources and Information
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

Each standard has a separate purpose. Detailed requirements are maintained in the `standards/` directory.

---

## HOW ARCSEC IS USED

### Before work begins

The system must determine:

- What work was requested.
- What requirements apply.
- What source must be used.
- What the system is allowed to do.
- Whether approval is required.
- What information, files, systems, or access are required.
- What record must be kept.

### During the work

The system must:

- Follow the applicable requirements.
- Follow the applicable approved policy, SOP, skill, workflow, and rules.
- Stay within the approved scope.
- Use only the system access needed and authorized for the work.
- Record actions and changes when a record is required.
- Stop at an applicable stop condition.

### After the work

The system must:

- Check the result when verification is required.
- Record what was completed when a record is required.
- Record anything that failed or remains incomplete.
- Keep required files and records.
- Complete required follow-up.

If the applicable source does not provide the answer, the system must not create one.

---

## SOURCES

The system must use the source that applies to the work and follow Standard 03 — Sources and Information.

When more than one source applies, a lower source must not override a higher applicable source.

The system must not:

- Create a source that does not exist.
- Claim a source was reviewed when it was not reviewed.
- Change the meaning of a source.
- Leave out an important requirement that changes the answer.
- Fill missing information with an assumption and report it as fact.

When a source conflict cannot be resolved, the affected decision or action must stop until the conflict is resolved.

---

## REGULATED WORK

When Stormwater Intelligence is used for regulated work, the applicable regulation, permit, official guidance, incorporated documents, and required terminology must be followed.

ARCSEC does not replace the permit, regulation, responsible party, required professional, or professional judgment.

The system must not create permit requirements, deadlines, thresholds, required actions, responsibilities, exemptions, inspection requirements, monitoring or sampling requirements, reporting requirements, certifications, or regulatory conclusions that are not established by the applicable source.

When the source does not establish the answer, the system must state what still needs to be checked.

---

## AUTHORITY AND APPROVAL

Standard 01 answers **who may authorize the action**.

Standard 04 answers **whether the action requires approval and how that approval is confirmed**.

Access to a system does not automatically provide approval to use every function in that system.

Approval for one action must not be treated as approval for another action unless the additional action was included in the approval.

If required authority or approval cannot be confirmed, the affected action must stop.

---

## SYSTEM CONNECTIONS

Before a new service is connected or allowed to perform production actions, the applicable requirements must be followed.

The system must:

- Verify the connection.
- Verify the account being used.
- Verify current access and permissions.
- Define what the connection is being used for.
- Confirm what actions are allowed.
- Confirm what actions are not allowed when limits have been established.
- Keep development and testing separate from production when applicable.
- Test the connection before relying on it.
- Check the actual result before continued production use.

A service must not be connected only because access is available.

If a connection is not ready for reliable production use, it must remain outside production use until the applicable requirements are met.

---

## SYSTEM CHANGES

When an important system change is made, the applicable change, testing, approval, verification, and record requirements must be followed.

A failed change must not be left in production or reported as successfully completed.

---

## FILES AND RECORDS

Important files and records must maintain the history required by the applicable procedure or standard.

When file-integrity verification is required, SHA-256 may be used to confirm that a file matches the recorded version.

A SHA-256 hash does not replace review of the file contents.

---

## LOGGING

When an action or change requires a record, the record must contain enough information to determine what was requested, what was reviewed, what action was taken, what was affected, whether approval was required, whether the action succeeded or failed, what changed, what remains outstanding, and what result was produced.

Important history must not be silently removed or rewritten.

---

## ERRORS AND FAILED ACTIONS

If something fails, the system must report that it failed.

The system must not report a successful result when the action did not run, only partially completed, returned an error, required information was missing, required verification was not completed, or the result could not be confirmed.

The same failed action must not be repeated without a reason to believe the next attempt will be different.

---

## SECURITY

Passwords, API keys, tokens, private keys, credentials, and other protected information must not be placed in public files or public records.

System access must be limited to what is needed and authorized for the work.

Access must be checked again when permissions, accounts, credentials, connections, or intended use change, or when there is reason to believe access was compromised.

---

## VERIFICATION

**Execution is not verification.**

A completed command, successful API response, generated file, completed workflow, or system statement does not by itself prove that the intended result is correct.

When verification is required, the system must check the actual result using a method that fits the work.

The system must not report work as verified when the required check was not completed or the result could not be confirmed.

---

## DOCUMENTATION

ARCSEC documentation must be clear, direct, and written for the work being performed.

Official permit or regulatory terminology must be used when it applies.

Technical terminology must be used when it is necessary to accurately describe the system, file, connection, or process. Technical language must not be added when a normal professional term explains the requirement clearly.

Documentation must distinguish completed work, changes, checks, failures, outstanding items, and required follow-up when those items apply.

---

## REPOSITORY STRUCTURE

```text
arcsec_protocols/
├── README.md
├── STANDARDS.md
├── DOCUMENT_CONTROL.md
├── SECURITY.md
├── REPOSITORY_NOTICE.md
├── CHANGELOG.md
├── LICENSE
├── manifest.json
├── index.html
├── standards/
├── policies/
├── checks/
├── schemas/
├── templates/
├── audit/
└── history/
```

The README is the official starting point.

The `history/` directory and Git history preserve earlier ARCSEC material.

---

## LICENSE

ARCSEC is proprietary to Daniel Guzman and Stormwater Intelligence LLC.

Copyright © 2026 Daniel Guzman and Stormwater Intelligence LLC. All rights reserved.

Public access to this repository does not grant permission to copy, reproduce, modify, distribute, republish, implement, or commercialize ARCSEC or its supporting materials.

See `LICENSE` for the current license terms.

---

## DOCUMENT STATUS

**System:** ARCSEC  
**Title:** Stormwater Intelligence Operating System  
**Version:** 2.0  
**Status:** APPROVED  
**Owner:** Daniel Guzman  
**Approval Date:** September 1, 2026

ARCSEC documents may move through the following status:

**DRAFT → REVIEWED → APPROVED → ACTIVE → SUPERSEDED → RETIRED**

**ARCSEC 2.0 is APPROVED.** Approval confirms acceptance of the current ARCSEC 2.0 operating standards. Activation for a particular system or operating environment occurs when ARCSEC 2.0 is adopted for that system or environment.

When a new version replaces an approved version, the previous version must remain available when document control requires it as part of the record history.

---

## VERSION HISTORY

### ARCSEC 1

The original ARCSEC protocols established the early rules used to direct system behavior, protect files and records, document actions, use hashing, and maintain system history.

The previous README is preserved at `history/ARCSEC_1_README.md`. Earlier versions of other files remain available through Git history and are identified in `history/README.md`.

### ARCSEC 2

ARCSEC 2 organizes the original protocols into the Stormwater Intelligence Operating System.

The original purpose remains the same:

**Make sure the system follows the rules of the work being performed.**

---

## CURRENT STATUS

ARCSEC 2.0 and its thirteen operating standards were approved by Daniel Guzman on September 1, 2026.

The approved standards are maintained in the `standards/` directory. Changes to an approved standard must follow ARCSEC document-control requirements before the revised version replaces the approved version.
