# Agent Identity & Trust Protocol (AITP)

Open protocol and reference implementations for issuing, delegating, and
verifying agent identity and trust across control planes and services.

## Repositories

| Repo | What it is |
|---|---|
| [`agentidentitytrustprotocol`](https://github.com/agentidentitytrustprotocol/agentidentitytrustprotocol) | The spec — JSON Schemas, RFCs, conformance fixtures. Source of truth. |
| [`aitp-rs`](https://github.com/agentidentitytrustprotocol/aitp-rs) | Core Rust workspace + the SDK bindings (npm/NAPI, Python/PyO3, WASM). The publish hub. |
| [`aitp-control-plane`](https://github.com/agentidentitytrustprotocol/aitp-control-plane) | Control-plane API service (Next.js). Consumes the npm SDK. |
| [`aitp-playground`](https://github.com/agentidentitytrustprotocol/aitp-playground) | Scenario runner / demo harness (FastAPI). Consumes the Python SDK. |
| [`aitp-verifier-py`](https://github.com/agentidentitytrustprotocol/aitp-verifier-py) | Independent second implementation of the verification core (spec conformance). |
| [`aitp-ui-console`](https://github.com/agentidentitytrustprotocol/aitp-ui-console) | Web console. |
| [`aitp-website`](https://github.com/agentidentitytrustprotocol/aitp-website) | Docs site. |
| [`aitp-ci`](https://github.com/agentidentitytrustprotocol/aitp-ci) | Shared CI/CD reusable workflows + the delivery standard. |

## Delivery

CI/CD is uniform across the org via [`aitp-ci`](https://github.com/agentidentitytrustprotocol/aitp-ci) —
see its [DELIVERY-STANDARD.md](https://github.com/agentidentitytrustprotocol/aitp-ci/blob/main/DELIVERY-STANDARD.md).
