# Custody & Multisig Model (v1)

Remapped Protocol follows a staged custody model designed to minimize surprise authority
while enabling early development.

## Bootstrap phase (current)
- Single-operator custody
- Explicitly temporary
- No public distribution
- No irreversible actions

This phase exists to reduce early operational complexity.

## Target custody architecture
The target model separates funds across independent multisigs:

| Bucket | Target control |
|------|----------------|
| Protocol Treasury | Long-term multisig custodians |
| Infrastructure Reserve | Ops-focused multisig |
| Development Fund | Core contributor multisig |
| Security & Audit Fund | Security-first multisig |
| Unallocated Buffer | Locked / governance decision required |

No single signer controls protocol funds.

## Multisig principles
- N-of-M threshold (e.g., 3-of-5 or 4-of-7)
- Distinct signer roles
- Replaceable signers via documented process
- Auditable actions

## Transition commitment
RMP will transition from bootstrap custody to multisig custody before:
- Public token distribution, or
- Expansion of incentive programs

Details will be published prior to transition.
