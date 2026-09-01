# ARCSEC Standard 11 — Workflow Requirements

**Version:** 2.0 Draft  
**Status:** DRAFT  
**Date:** September 1, 2026

## PURPOSE

This standard defines how workflows are documented, tested, approved, and changed.

## REQUIRED CONTENT

An ARCSEC-controlled workflow must identify:

- Workflow name and version.
- Status.
- What starts the workflow.
- Required inputs.
- Expected outputs.
- The steps performed and their order.
- Required systems, files, data, services, or skills.
- Dependencies that must be available before a step runs.
- Decisions made during the workflow and the information used for those decisions.
- Where approval is required.
- Stop conditions.
- What happens when a step partially completes or fails.
- How the final result is checked.
- What record is kept when required.

## REQUIREMENTS

A workflow must follow higher applicable ARCSEC standards, policies, and SOPs.

A workflow must not skip or bypass a required step because another system, service, or tool can bypass it.

A workflow must not continue past a stop condition unless the condition has been resolved and continuation is allowed by the applicable requirement.

Changes to an ACTIVE workflow must be documented and tested before production use.

The test must confirm the required path, applicable approval points, stop conditions, failure handling, and expected output.

## STATUS

This standard remains **DRAFT** until reviewed and approved.
