# Terrynce White

Receiver-owned authorization: the system receiving an agent's request decides what the agent may do, not the agent's vendor.

OpenLine carries the owner's authority to the receiver and records the receiver's decision with signed receipts.

## Start here

**[openline-wallet](https://github.com/terryncew/openline-wallet)** — portable authority wallet: mandates, revocations, verified history across model and provider change.

## The stack

**Receiver gates** — the enforcement points.
- [openline-receipt-gate](https://github.com/terryncew/openline-receipt-gate): one-line gate in front of risky calls; mandate profiles, decision receipts.
- [openline-airlock](https://github.com/terryncew/openline-airlock): holding area; risky actions wait until the receiving system decides. Bring-your-own-agent adapters.
- [openline-lite](https://github.com/terryncew/openline-lite): small verified handoffs.

**Wire format** — what travels between systems.
- [olp-wire-canon](https://github.com/terryncew/olp-wire-canon): normative wire format and conformance suite for portable receipts.
- [openline-core](https://github.com/terryncew/openline-core): the 2025 protocol origin. Preserved as research reference.

**Evidence** — what proves what happened.
- [openline-otel](https://github.com/terryncew/openline-otel): portable signed receipts from OpenTelemetry traces.
- [openline-claim-graph](https://github.com/terryncew/openline-claim-graph): source-anchored claim graphs — what supports what, what changed, what breaks downstream.

**World** — the shared testbed.
- [openline-world](https://github.com/terryncew/openline-world): shared-agent world, local developer preview. Agents act only through receiver-owned authorization; owners hold their own authority.

**Conformance** — what "correct" means.
- [agent-authority-conformance-benchmark](https://github.com/terryncew/agent-authority-conformance-benchmark): authority-lifecycle conformance (delegation → revocation → restart → owner-key replacement → single-use replay). Experimental, for public review.

## Provenance

What I thought, and when: [Sir Terrynce's Almanac](https://terrynce.substack.com).
What I built, and when: this account. Frozen experiment records stay frozen; superseded work stays in the history.
