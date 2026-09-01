# ARCSEC Security

**Version:** 2.0 Draft  
**Status:** DRAFT  
**Date:** September 1, 2026

ARCSEC requires protected information and system access to be handled carefully.

## Protected Information

Do not place the following information in public files or public records:

- Passwords.
- API keys.
- Access tokens.
- Private keys.
- Security codes.
- Other credentials or protected account information.

## System Access

Before using a connected system:

- Verify the account being used.
- Verify the access and permissions.
- Confirm what the connection is being used for.
- Confirm what actions are allowed.
- Keep development and testing separate from production when applicable.

Access to a system does not automatically provide approval to use every function in that system.

## Exposure or Unauthorized Change

If protected information is exposed or an unauthorized change is found:

- Stop using the affected access when necessary.
- Protect the affected account or system.
- Record what happened.
- Replace or revoke exposed credentials when required.
- Verify the system before returning it to normal use.

Do not publish credentials in issues, commits, logs, screenshots, examples, or documentation.
