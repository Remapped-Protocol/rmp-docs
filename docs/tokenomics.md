# Token Allocation & Vesting (v1)

The RMP token is a native asset on the Remapped Protocol chain.

It exists solely to fund development, infrastructure, and security.
It does not grant governance power and is not required to use messaging or identity features.

## Token properties
- Total supply: 250,000,000 (fixed)
- Issued at genesis
- No inflation
- No mining
- No token-based governance
- Not required for protocol usage

## Design intent
Vesting is used to rate-limit access to allocated balances.
This reduces surprise liquidity events and aligns incentives over time.

Early availability exists only to provide operational runway.

## Allocation (v1)

| Bucket | Percentage |
|------|------------|
| Protocol Treasury | 32% |
| Infrastructure Reserve | 23% |
| Development Fund | 22% |
| Security & Audit Fund | 8% |
| Community / Early Supporters | 7% |
| Unallocated Buffer | 8% |

All tokens are issued at genesis.

The Unallocated Buffer remains locked and may only be assigned via a transparent governance decision (or burned).

## Vesting & availability

### Development Fund
- 15% unlocked at genesis
- 85% vests linearly over 48 months

### Infrastructure Reserve
- 20% unlocked at genesis
- 80% vests over 36 months

### Security & Audit Fund
- 30% unlocked at genesis
- 70% vests over 24 months

### Community / Early Supporters
- 12-month cliff
- Then 36-month linear vest

### Protocol Treasury
- No meaningful early unlock
- 60–72 month linear vest

### Unallocated Buffer
- Locked

## Transparency
All allocations and vesting schedules are intended to be auditable and published prior to execution.
