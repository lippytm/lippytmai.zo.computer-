# P-011-CRM-001 — Bounded Zo CRM Runtime Contract

**Canonical source:** `lippytm/Prompt-11-`  
**Status:** Q2 architecture mirror

## Permitted first experiment

Run the standard-library Prompt #11 CRM control-plane prototype with synthetic or public records only. The experiment may validate deterministic IDs, consent checks, duplicate suggestions, mission routing, SLA detection, data-quality scores, release blocking, audit events, database integrity, backup, and restore.

## Runtime Experiment Passport

Before execution record:

- experiment ID, owner, repository, branch, commit, and hashes;
- objective and acceptance criteria;
- synthetic/public dataset manifest;
- permitted and prohibited data classes;
- tools, network destinations, and connector scopes;
- secret-management method;
- cost and computational-credit limit;
- timeout and rate limits;
- logging, monitoring, and correlation IDs;
- backup and restore method;
- rollback, shutdown, credential revocation, correction, and retirement;
- required gates and human decision.

## Prohibited data and actions

- real production customer or learner records without Q3 approval;
- passwords, API keys, wallet seeds, private identity documents, banking details, medical records, or confidential whistleblower evidence;
- social publishing or marketing outreach;
- silent identity merging or consent changes;
- payment, refund, contract, investment, or asset actions;
- autonomous production deployment;
- unrestricted web or repository access.

## Environment separation

- **Development:** local or isolated synthetic tests.
- **Sandbox:** bounded Zo run with explicit resource controls.
- **Pilot:** limited Q3 use after security, privacy, accessibility, and connector review.
- **Production:** prohibited until separate Q4 certification and HumanApprovalGate.

## Test sequence

1. Verify commit and artifact hashes.
2. Initialize an empty SQLite database.
3. Apply versioned migrations.
4. Import synthetic records.
5. Run all CRM unit and contract tests.
6. Run consent, suppression, duplicate, SLA, attribution, and release-blocking diagnostics.
7. Create and verify backup.
8. Restore into a clean database and compare counts and integrity.
9. Export an audit and Quality Evidence Packet.
10. Shut down and revoke temporary permissions.

## Acceptance evidence

- test logs and exit status;
- database integrity result;
- source and restored table counts;
- resource and cost usage;
- permission and network record;
- backup and restore proof;
- defect and correction records;
- human Q3 decision.

## Current boundary

This contract does not claim that Zo credentials, connectors, or a synchronized CRM runtime are currently configured. Production use remains prohibited.
