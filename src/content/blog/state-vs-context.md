---
title: "State vs. Context: Mapping Information Flow in Distributed Teams"
description: "The persistent conflation of application state with operational context is the root cause of most distributed team coordination failures. Here is the corrective mental model."
pubDate: 2026-05-05
tags: ["Architecture", "Methodology"]
---

# State vs. Context: Mapping Information Flow in Distributed Teams

In distributed systems, we make a rigorous distinction between **state** (the authoritative record of current reality) and **context** (the information required to interpret or act on state). Most engineering teams never apply this distinction to their own organizational operation.

## The Conflation Problem

When teams conflate state and context, they produce:

- Status meetings that rehash completed work rather than resolve blockers
- Documentation that records decisions without recording the rationale
- Escalations that carry context but not the state needed to act on it

## The Corrective Model

Map every information artifact to one of two buckets:

**State artifacts**: Source of truth. Single-owner. Versioned.
**Context artifacts**: Interpretive layer. Multi-author. Ephemeral.

The pathology emerges when context artifacts are treated as state — when a Slack thread becomes the authoritative record of a decision.

## Structural Resolution

Implement a decision log (state artifact) with a mandatory rationale field. Every team decision must produce a timestamped record with: decision, alternatives considered, and the deciding context.
