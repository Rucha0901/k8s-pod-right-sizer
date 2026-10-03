---
name: resource-sizing
description: Specialized capability for Analyzes historical CPU, memory, and OOM kill telemetry to optimize resource requests and limits across Kubernetes deployments.
license: MIT
allowed-tools: ""
metadata:
  author: "Rucha Salpure"
  version: "1.0.0"
  category: devtools
---

# Kubernetes Pod Right-Sizer Agent — Resource Sizing Skill

## Purpose
The `resource-sizing` capability provides high-assurance execution routines for `Kubernetes Pod Right-Sizer Agent`.

## Execution Workflow
1. Validate input parameters against typed schemas and invariant constraints.
2. Ingest contextual metrics and establish a deterministic baseline.
3. Formulate candidate recommendations with explicit confidence intervals.
4. Submit draft plans to the independent checker agent for verification.

## Boundary Conditions
- **Input validation:** Reject non-conforming or malformed payloads before evaluation.
- **Fail-safe:** Escalate immediately if telemetry indicators exhibit critical anomalies.
