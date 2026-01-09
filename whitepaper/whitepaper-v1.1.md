# Remapped Protocol (RMP)
## Resilient Messaging Verification & Identity Infrastructure

**Version:** v1.1  
**Date:** January 2026  
**Status:** Informational

This document mirrors the canonical whitepaper published at:
https://remappedprotocol.org/Remapped_Protocol_Whitepaper_v1.1.pdf

The PDF is the authoritative presentation.
This Markdown version exists for transparency and version tracking.

---

## 1. Motivation

Modern communication systems rely on centralized infrastructure and continuous connectivity.
In degraded environments—natural disasters, outages, censorship, or infrastructure failure—
message verification and identity assurance become unreliable or impossible.

Remapped Protocol (RMP) addresses a narrow but critical problem:

**How can messages and identities be verifiably attested without requiring continuous connectivity,
centralized trust, or speculative incentives?**

RMP prioritizes verifiability, predictability, and operational resilience over growth or monetization.

---

## 2. Non-Goals

RMP explicitly does not attempt to be:

- A general-purpose smart contract platform
- A replacement for messaging applications
- A DAO or token-governed system
- A yield, mining, or staking network
- A pay-to-use communication service

These exclusions are intentional.

---

## 3. System Overview

RMP consists of three primary components:

1. **Messaging Verification Layer**
   - Messages are signed off-chain
   - Message content is never stored on-chain
   - On-chain records act as attestations only

2. **Identity Controls**
   - Deterministic identity rules
   - Explicit authority boundaries
   - No privileges derived from token ownership

3. **Substrate-Based Chain Runtime**
   - Native asset
   - Fixed supply
   - No inflation
   - No token-based governance

The system is designed to function under intermittent connectivity and asynchronous participation.

---

## 4. Threat Model & Security Posture

RMP assumes:
- Adversarial network conditions
- Partial node failure
- Operator churn
- Delayed synchronization
- No trusted central operator

Security design emphasizes:
- Constrained authority
- Auditable actions
- Predictable behavior over flexibility

Emergency actions are intentionally limited and logged.

---

## 5. Governance Model

Governance in RMP is **not token-based**.

Key properties:
- No governance power from token ownership
- Council-based governance with constrained authority
- No unrestricted master keys or sudo
- Emergency powers are limited, auditable, and time-bound

Governance exists to maintain protocol integrity—not to extract value.

---

## 6. Token Scope

The RMP token is a native asset on the RMP chain.

**Properties**
- Fixed supply: 250,000,000
- Issued at genesis
- No inflation
- No mining
- No staking yield
- No governance rights
- Not required for messaging or identity usage

The token exists solely to fund:
- Development
- Infrastructure
- Security
- Long-term sustainability

---

## 7. Token Allocation & Vesting

Token allocation is intentionally conservative.

### Allocation (v1)
- Protocol Treasury — 32%
- Infrastructure Reserve — 23%
- Development Fund — 22%
- Security & Audit Fund — 8%
- Community / Early Supporters — 7%
- Unallocated Buffer — 8%

All tokens are issued at genesis.
Access to allocations is rate-limited via vesting schedules.

Early availability exists only to provide operational runway.

---

## 8. Node Incentive Pilot

RMP does not use mining or inflationary rewards.

Instead, it operates a **Node Incentive Pilot**:
- Funded from the Infrastructure Reserve
- Budgeted and time-bounded
- Flat stipends (not yield)
- Manual admission during pilot
- No open-ended commitments

These incentives are operational reimbursements, not profit mechanisms.

---

## 9. Custody Model

RMP follows a staged custody approach.

### Bootstrap Phase
- Single-operator custody
- Explicitly temporary
- No public distribution
- No irreversible actions

### Target State
- Separate multisigs per allocation bucket
- No single-party control
- Transparent signer replacement
- Clear emergency constraints

Transition occurs before public expansion or large-scale incentives.

---

## 10. Roadmap Philosophy

RMP does not publish speculative timelines.

Milestones are published only when:
- Scope is locked
- Risks are understood
- Execution is feasible

Accuracy is prioritized over optimism.

---

## 11. Conclusion

Remapped Protocol is intentionally narrow, conservative, and predictable.

It favors:
- Resilience over speed
- Verification over throughput
- Transparency over flexibility
- Sustainability over speculation

RMP is infrastructure designed to function quietly—especially when other systems fail.
