# ARCSEC Standard 13 — Verification and Record History

**Version:** 2.0 Draft  
**Status:** DRAFT  
**Date:** September 1, 2026

## PURPOSE

This standard defines how completed work is checked and how records are maintained.

## CORE RULE

**Execution is not verification.**

A completed command, successful API response, generated file, completed workflow, or system statement does not by itself prove that the intended result is correct.

## REQUIREMENTS

After work that requires verification is completed, the system must:

- Use a verification method that fits the work.
- Check the actual result, not only whether the action ran.
- Record what was completed when a record is required.
- Record anything that failed or remains incomplete.
- Keep the required files and records.
- Keep previous versions when they are required to remain part of the record.

Verification may include:

- Reviewing the controlling or supporting source.
- Checking the final file or record.
- Confirming the actual state of the affected system.
- Comparing expected and actual results.
- Comparing records.
- Checking a SHA-256 hash when file-integrity verification is required.

When the applicable procedure requires an independent check, the same unverified output must not be used as its own verification.

The system must not report work as verified when the required check was not completed or when the result could not be confirmed.

## RECORD HISTORY

When previous versions are required to remain part of the record, a new version must not silently replace the previous version.

Corrections and superseded versions must remain identifiable when document control requires that history.

## STATUS

This standard remains **DRAFT** until reviewed and approved.
