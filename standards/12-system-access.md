# ARCSEC Standard 12 — System Access

**Version:** 2.0  
**Status:** APPROVED  
**Approval Date:** September 1, 2026

## PURPOSE

This standard defines how system access, credentials, connections, and permissions are handled.

## BEFORE ACCESS IS USED

Before using a connected system, the system must:

- Verify the account being used.
- Verify the current access and permissions.
- Confirm what the connection is being used for.
- Confirm what actions are allowed.
- Confirm what actions are not allowed when limits have been established.
- Keep development and testing separate from production when applicable.

Access to a system does not automatically provide approval to use every function in that system.

## ACCESS LIFECYCLE

Access must be checked again when:

- Permissions change.
- The account or authorized role changes.
- Credentials are replaced or expire.
- A connection is reconfigured.
- The connection is being used for a new purpose.
- There is reason to believe credentials or access were exposed or compromised.

Access that is no longer authorized or needed must not continue to be used.

Compromised or exposed credentials must be revoked, replaced, or otherwise secured before normal use resumes when the affected system allows that action.

## PROTECTED INFORMATION

Passwords, API keys, tokens, private keys, credentials, and other protected information must not be placed in public files or public records.

Protected information must not be exposed merely to prove that access exists.

## STATUS

This standard is **APPROVED** as part of ARCSEC 2.0.