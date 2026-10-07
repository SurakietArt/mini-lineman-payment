# mini-lineman-payment

payment-service (Python / Django). Mock payment with idempotency keys and a webhook callback.

Separate repo on purpose: sensitive, restricted access, independent deploy cadence.

Status: **skeleton only.** No service code yet.

Part of the mini-lineman system. Architecture, phases and conventions live in the
`mini-lineman` repo (`CLAUDE.md`); decisions are recorded as ADRs in
`mini-lineman/docs/decisions/`.

## Toolchain

Pinned by ADR 0001: Python 3.14.8. CI runs inside
`ghcr.io/surakietart/mini-lineman-py-tools`.
