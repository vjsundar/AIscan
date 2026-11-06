# Controlled POC Test Methodology

1. Review each fixture and the expected result in `manifests/test-cases.json`.
2. Publish only these synthetic fixtures to approved locations controlled by the domain owner.
3. Record exact publication URLs and timestamps in a private execution log.
4. Use only approved public search interfaces, public repository search, permitted public file-sharing/paste sources, and approved threat-intelligence feeds.
5. Do not authenticate to third-party systems, bypass access controls, probe hosts, or expand scope beyond the approved domain association and sources.
6. Collect minimal evidence and deduplicate findings.
7. Have the designated human reviewer classify each finding.
8. Remove the public fixtures after the test window and verify removal where feasible.

## Metrics

- Positive-case recall = discoverable positive fixtures detected / all discoverable positive fixtures.
- Negative-case false-positive rate = negative fixtures incorrectly flagged / all negative fixtures.
- Classification accuracy: domain mention vs potential exposure.
- Deduplication quality.
- Evidence sufficiency and redaction quality.
- Source coverage, failures, and limitations.
- Analyst review time per finding.

A small synthetic corpus does not demonstrate comprehensive internet coverage. Report only the sources and interfaces actually tested.
