---
category: runbook
title: Notifications API runbook
description: On-call runbook for Notifications API.
related_entities:
  - notifications-api
related_teams:
  - notifications
---

# Notifications API runbook

On-call guide for `notifications-api` (Notifications, tier high).

## Alerts

- **notifications-api-high-error-rate** — 5xx over 2% for 5m. Check upstream dependencies.
- **notifications-api-latency** — p99 over SLO. Check resource saturation.

## Common issues

- **Pod OOMKilled** — check memory limits and recent traffic spikes.
- **Crashloop** — check the last deploy and roll back if needed.

## Escalation

Page the Notifications on-call rotation.

