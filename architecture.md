# System Architecture

## Component Overview

```
┌────────────────────────────────────────────────────────┐
│                    USER LAYER                          │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐    │
│  │  Matchify   │  │  Partner    │  │  Direct     │    │
│  │  (Consumer) │  │  Apps       │  │  Protocol   │    │
│  └──────┬──────┘  └──────┬──────┘  └──────┬──────┘    │
└─────────┼────────────────┼─────────────────┼──────────┘
          │                │                 │
┌─────────▼────────────────▼─────────────────▼──────────┐
│                   GHOST LAYER                          │
│  ┌──────────────────────────────────────────────┐     │
│  │  AI Ghost Network (Ghost-to-Ghost Protocol)  │     │
│  │  - Matching · Negotiation · Scheduling       │     │
│  │  - Transaction Execution · Content Gen       │     │
│  └──────────────────────────────────────────────┘     │
└───────────────────────┬───────────────────────────────┘
                        │
┌───────────────────────▼───────────────────────────────┐
│                INFRASTRUCTURE LAYER                    │
│  ┌────────────┐  ┌────────────┐  ┌────────────┐       │
│  │  CDO-Chain │  │  P2P Cloud │  │  Oracles   │       │
│  │  (L2)      │  │  (Storage) │  │  (Bridges) │       │
│  └────────────┘  └────────────┘  └────────────┘       │
└───────────────────────────────────────────────────────┘
```

## CDO-Chain

| Property | Specification |
|----------|---------------|
| Type | Optimistic Rollup (L2) |
| Settlement | Ethereum-secured |
| TPS Target | 100,000+ |
| Gas Cost | <$0.0001 |
| Finality | <1 second |

> **Note:** These are *design targets* subject to rollup parameters, data availability layer choice, and third-party audits. Final specifications may vary based on production optimization.

**Key on-chain components:**
- Asset ownership records
- Ghost registry (soul-bound)
- Social graph (relationships)
- Transaction settlement
- Governance votes

### Progressive Decentralization

| Phase | Timeline | Validator Set | Governance |
|-------|----------|---------------|------------|
| **Launch** | Q4 2026 | Foundation-operated | Core team |
| **Phase 1** | 2027 H1 | Permissioned validators | Token voting |
| **Phase 2** | 2027 H2 | Open validator set | DAO-controlled |
| **Phase 3** | 2028+ | Fully decentralized | Protocol ossification |

## P2P Cloud (Distributed Storage)

Built on Proof of Replication (PoRep) + Proof of Spacetime (PoSt):
- User data encrypted with user keys
- No platform access to data
- Automatic redundancy
- True deletion (not just database flags)

### User Data Rights (GDPR-aligned)

| Right | Implementation |
|-------|----------------|
| **Access** | Export all data anytime via dashboard |
| **Portability** | Standard formats, no vendor lock-in |
| **Deletion** | Cryptographic deletion (keys destroyed, data unrecoverable) |
| **Rectification** | Users modify their data directly |
| **Objection** | Opt-out of any data processing |

**Candao cannot read, sell, or monetize user data. Period.**
