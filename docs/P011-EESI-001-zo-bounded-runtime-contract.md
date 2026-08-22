# P-011-EESI-001 — lippytmai.zo.computer Bounded Runtime Contract

**Canonical source:** `lippytm/Prompt-11-` — P-011-EESI-001  
**Role:** controlled sandbox and prototype runtime for approved EESI work packets  
**Human owner and final approver:** Charles Earl Lipshay

## 1. Purpose

This contract defines how lippytmai.zo.computer may be used for bounded experiments involving the Charles Earl Lipshay AI Clone Interface, Fabric Hermes, Fable 5, AI swarms, learning products, and Ethical Revenue Machine prototypes.

A repository document does not prove that a Zo workspace, API, credential, deployment, or synchronization pathway is active. Every runtime experiment requires separate verification.

## 2. Runtime Experiment Passport

Every Zo experiment requires:

- experiment ID and version;
- human owner;
- objective and scope;
- source work packet;
- code and artifact versions;
- privacy class;
- approved datasets;
- prohibited datasets;
- model line;
- tools and services;
- credential reference, never secret value;
- maximum runtime;
- maximum cost;
- expected outputs;
- tests and acceptance criteria;
- monitoring and log destination;
- rollback and shutdown procedure;
- connector revocation procedure;
- human reviewer;
- HumanApprovalGate status.

## 3. Permitted initial uses

- run the standard-library EESI Evolution Engine;
- validate JSON and YAML contracts;
- execute unit tests;
- generate synthetic mutation proposals;
- build public-data-only programming and blockchain lessons;
- render approved Educational Entertainment prototypes;
- test bounded queues, work packets, and audit events;
- measure runtime, cost, errors, and reliability;
- package artifacts for human review.

## 4. Prohibited uses

- storing passwords, API keys, private keys, seed phrases, recovery codes, payment data, full medical records, private financial records, identity documents, confidential witnesses, or unredacted restricted evidence in source code or general logs;
- impersonating Charles Earl Lipshay;
- generating fabricated personal memories or approvals;
- granting the runtime unrestricted access to all repositories or accounts;
- autonomous payments, contracts, borrowing, investing, tax filing, wallet creation, or asset transfer;
- deploying self-modifying code without review;
- public release, sales, minting, or franchise replication without applicable gates and human approval;
- training on data without documented rights and permissions;
- allowing an experiment to continue after its budget, time limit, or stop condition is reached.

## 5. Environment separation

Required environments:

- `development` — local or isolated code construction;
- `sandbox` — synthetic or approved public data only;
- `pilot` — bounded users and approved internal data, if separately authorized;
- `production` — prohibited until a separate Q4 decision and runtime certification.

Do not reuse production credentials in development or sandbox.

## 6. Secrets and permissions

- use an approved secret store where supported;
- never commit secrets to GitHub;
- use one credential per bounded purpose where practical;
- minimize scopes and expiration;
- record who approved access and when;
- rotate or revoke credentials after incidents, personnel changes, or experiment completion;
- confirm revocation rather than assuming it succeeded;
- review service-account and connector permissions before every new data class is introduced.

## 7. Test sequence

1. Verify code and configuration hashes.
2. Verify approved data classification.
3. Run unit and schema tests.
4. Run the experiment with synthetic records.
5. Verify no network or connector access beyond the approved scope.
6. Record runtime, cost, latency, errors, and outputs.
7. Test failure, timeout, rollback, and shutdown.
8. Review logs for secrets or restricted data.
9. Export only approved artifacts and evidence.
10. Revoke temporary access.
11. Record the result in GitHub, MEPL, and the Continuation Packet.

## 8. Evolution Engine pilot

**Experiment ID:** `ZO-EESI-PILOT-001`

### Objective

Run the canonical standard-library Evolution Engine against synthetic Clone Passport and capability-evaluation records.

### Expected result

- unit tests pass;
- deterministic mutation proposals are generated;
- proposals remain `pending` for human approval;
- no source code modification occurs;
- no external network, payment, contract, publishing, or identity action occurs;
- cost and runtime remain within the approved zero- or low-cost ceiling.

### Stop conditions

- unexpected network request;
- missing test;
- nondeterministic output without explanation;
- restricted-data exposure;
- permission escalation;
- cost or runtime overage;
- attempt to pass HumanApprovalGate;
- attempt to deploy or execute a financial action.

## 9. Swarm pilot boundary

A future Zo swarm pilot must begin with no more than a small bounded roster and one work packet. Each agent requires an Agent Passport, tool scope, data class, budget, timeout, output schema, tests, and stop conditions.

The first swarm may prepare evidence and proposals. It may not autonomously publish, mint, charge, contract, or create a new production agent.

## 10. Audit evidence

Record:

- experiment and work-packet IDs;
- code commit and content hashes;
- environment and dependency versions;
- start and end timestamps;
- owner and reviewer;
- approved permissions;
- test results;
- runtime and cost;
- outputs and artifact hashes;
- incidents and defects;
- rollback or shutdown evidence;
- credential revocation status;
- decision and next action.

## 11. Current boundary

This contract is an architecture and safety specification. It does not claim that a Zo connector is configured, that credentials are available, that the EESI pilot has run on Zo, or that any production deployment exists.
