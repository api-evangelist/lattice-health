# Lattice Health

AI governance as a managed service for hospitals. Lattice Health monitors every clinical AI model running across vendors in a hospital by tapping the HL7 and DICOM signals those models already emit, then delivers a per-role cryptographically signed PDF report each morning covering drift (PSI), subgroup fairness disparity, safety posture, latency, silent vendor model-update detection, and aggregated radiologist feedback. Reports are signed with the institution's own key and verify offline with standard open-source tooling.

- Website: https://www.latticehealthai.com/
- Y Combinator: https://www.ycombinator.com/companies/lattice-health (Spring 2026, San Francisco)
- Backed by: y-combinator

## Developer surface

As of 2026-07-19 Lattice Health publishes **no public API**, developer portal, API reference, machine-readable specification, SDKs, CLI, sandbox, changelog, status page, or pricing. The product ships as an on-premise / private-cloud managed service with signed PDF and evidence-packet outputs. This repo therefore carries identity, conformance, and security-posture artifacts only.

## Artifacts

| Artifact | File |
|---|---|
| APIs.json profile | `apis.yml` |
| Standards conformance (vendor claims) | `conformance/lattice-health-conformance.yml` |
| Domain security posture (probed) | `security/lattice-health-domain-security.yml` |
| Well-known discovery probe (all 404) | `well-known/lattice-health-well-known.yml` |
| llms.txt | `llms/lattice-health-llms.txt` |
