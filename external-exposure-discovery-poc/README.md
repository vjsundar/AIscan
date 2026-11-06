# External Data Exposure Discovery POC

**Status:** Synthetic test corpus only  
**Target domain:** `harvexhub.com`  
**Visibility:** Public

This directory contains harmless synthetic fixtures for evaluating a bounded external data-exposure discovery workflow. It is not production platform code and contains no real client information, personal data, passwords, API keys, access tokens, or confidential business material.

## Safety and use

- All people, organizations, projects, identifiers, and campaign details are fictional.
- Credential-like strings are deliberately nonfunctional placeholders.
- Do not replace fixtures with real client data or live secrets.
- Do not use these fixtures as permission to probe, authenticate to, or scan third-party systems.
- Discovery must use approved public interfaces and sources, respecting source terms and applicable law.
- A domain mention alone is not evidence of a data exposure.
- Findings require human validation. The designated reviewer is the domain owner.

## Corpus layout

- `test-corpus/` — synthetic positive and negative examples.
- `manifests/test-cases.json` — expected classifications and rationale.
- `docs/finding-schema.md` — suggested finding record.
- `docs/test-methodology.md` — controlled test method and metrics.

## Publication note

This corpus is intentionally separated from production platform source code. Keep it synthetic-only and remove public fixtures after the test window.
