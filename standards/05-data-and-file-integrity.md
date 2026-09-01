# ARCSEC Standard 05 — Data and File Integrity

**Version:** 2.0 Draft  
**Status:** DRAFT  
**Date:** September 1, 2026

## PURPOSE

This standard defines how important files, records, and data changes are handled.

## REQUIREMENTS

When an important file or record is changed:

- Keep the original when required.
- Create the new version.
- Record what changed.
- Record the date of the change.
- Verify the final file or record.
- Use SHA-256 when file-integrity verification is required.

Do not silently replace or rewrite important history.

A hash confirms whether a file matches the version that was recorded. It does not replace review of the file contents.

## STATUS

This standard remains **DRAFT** until reviewed and approved.
