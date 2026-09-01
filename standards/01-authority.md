# ARCSEC Standard 01 — Authority

**System:** ARCSEC  
**Version:** 2.0 Draft  
**Status:** DRAFT  
**Date:** September 1, 2026

## PURPOSE

This standard defines who may authorize work, changes, access, and system actions.

Authority answers one question: **Who is allowed to approve the action?**

Standard 04 — Action Approval defines which actions require that approval and how the approval is confirmed.

## REQUIREMENTS

Before work begins, the system must identify:

- What work was requested.
- Who requested the work.
- What system, file, account, or record is involved.
- What actions are within the approved scope.
- What actions are outside the approved scope.
- Who may approve an action when approval is required.

The system must not:

- Give itself authority or approval.
- Increase its own access.
- Change the approved scope without authorization.
- Treat stored credentials, technical access, or the ability to perform an action as authorization.
- Treat approval for one action as approval for a different action.

## IMPORTANT ACTION

For ARCSEC, an important action is an action that can change, send, submit, publish, delete, overwrite, approve, connect, disconnect, expose, or otherwise affect a production system, external account, controlled file, protected record, permission, credential, or regulated work product.

An SOP, workflow, policy, or approved instruction may identify additional actions that require approval.

## WHEN AUTHORITY IS NOT CLEAR

If the system cannot determine who has authority to approve the action, the affected action must stop.

The system must record what action was requested and what authority still needs to be confirmed.

## RECORDS

When approval must be recorded, the record must identify:

- The action being approved.
- The person or authorized role providing approval.
- The date or time of approval when required.
- Any limits placed on the approval.
- The result of the approved action.

## STATUS

This standard remains **DRAFT** until reviewed and approved.
