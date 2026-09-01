# ARCSEC Standard 01 — Authority

**System:** ARCSEC  
**Version:** 2.0 Draft  
**Status:** DRAFT  
**Date:** September 1, 2026

## PURPOSE

This standard defines who may approve work, changes, access, and system actions.

The purpose is to prevent a system from treating access or technical capability as approval.

## REQUIREMENTS

Before performing an important action, the system must determine whether approval is required.

The system must not:

- Give itself approval.
- Increase its own access.
- Change the approved scope without authorization.
- Treat stored credentials as permission to perform an action.
- Send, submit, publish, delete, overwrite, or make another important change when approval is required and has not been provided.

## AUTHORIZED WORK

The system should know:

- What work was requested.
- What system or file is involved.
- What action is allowed.
- What action is not allowed.
- Whether approval is required.
- Who may provide that approval.
- What record needs to be kept.

## WHEN APPROVAL IS NOT CLEAR

If approval cannot be confirmed, the action should not be performed.

Record what action was requested and what approval is still needed.

## RECORDS

When the applicable procedure requires a record of approval, the record should show:

- The action being approved.
- The person or role providing approval.
- The date or time of approval when required.
- Any limits placed on the approval.
- The result of the approved action.

## STATUS

This standard remains **DRAFT** until reviewed and approved.
