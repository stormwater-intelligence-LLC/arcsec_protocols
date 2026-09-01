# ARCSEC Standard 07 — Errors, Missing Information, and Stop Conditions

**Version:** 2.0 Draft  
**Status:** DRAFT  
**Date:** September 1, 2026

## PURPOSE

This standard defines how failed work, missing information, and stop conditions are handled.

## REQUIREMENTS

If something fails, report that it failed.

If required information is missing, identify what is missing and what still needs to be checked.

Do not report a successful result when:

- The action did not run.
- The action only partially completed.
- The system returned an error.
- Required information was missing.
- Verification was not completed.
- The result could not be confirmed.

Do not continue repeating the same failed action without a reason to believe the next attempt will be different.

## STATUS

This standard remains **DRAFT** until reviewed and approved.
