# How Partners Earn

> **Partners don't profit by taxing users. Partners profit by growing the network.**  
> Candao replaces fee extraction with **performance-based protocol rewards** and **direct business revenue**.

---

## TL;DR

Most apps earn by taking a cut from every transaction.  
Candao flips this:

- You **commit to Zero Fee** (no platform-style cuts)
- Users join through **Infinite Package** ($100 CDO)
- The protocol rewards you with **CDO allocations** based on:
  **active users + retention + cross-ecosystem contribution**

This is not charity. It's **engineered economics**.

---

## The Core Shift

Traditional apps monetize via:
- platform fees (10–30%)
- subscriptions
- ads & data extraction

**Candao flips it:**

The app owner commits to Zero Fee and earns through:

1. **Protocol rewards (CDO pool)** — rewards linked to verified network contribution  
2. **Direct revenue** — selling products/services directly (no marketplace tax)  
3. **Reduced build cost** — AI-accelerated + community execution lowers development spend  
4. **Utility-driven demand exposure** — adoption increases CDO utility demand (no guarantees)

> **Zero Fee does not mean zero revenue.**  
> It means we remove rent extraction and replace it with network-aligned rewards.

---

## Partner Entry: The $1,000+ CDO Commitment

A partner enters by holding:

| Requirement | Details |
|---|---|
| **CDO commitment** | $1,000+ worth (varies by partner/business scope) |
| **Purpose** | Alignment bond (not a fee) |
| **Operating model** | Zero Fee (no platform cuts) |
| **Mission** | Onboard users into Infinite Package + grow the 360° community |

This is not a "pay us" fee. It's a **protocol alignment bond**.

### Token Lock Schedule

Partner tokens are locked with gradual unlock:

| Year | Unlock | Cumulative |
|------|--------|------------|
| 1 | 0% | 0% liquid |
| 2 | 10% | 10% liquid |
| 3 | 10% | 20% liquid |
| 4 | 40% | 60% liquid |
| 5 | 40% | 100% liquid |

> **Zero-fee access and partner benefits continue throughout the lock period.** The lock removes tokens from circulation, creating healthier tokenomics for everyone.

---

## What Partners Receive

### 1. Apps Built by the 360° Community

Instead of paying agency rates, partners access an ecosystem pipeline:

- AI-accelerated development (improving monthly)
- Multirole contributors (devs, designers, marketers, operators)
- MVP-first delivery with reusable modules

Contributors earn via community reward mechanisms and project-aligned incentives.

### 2. Happier Customers Through Lower Prices

Because you operate Zero Fee:
- Customers pay less (no middleman tax)
- Higher perceived value per dollar
- Stronger retention and loyalty

### 3. CDO Reward Pools Replace "Fee Profit"

Instead of a cut on every transaction, the protocol allocates rewards:

| Your Contribution | Your Reward |
|-------------------|-------------|
| Users onboarded | CDO allocation |
| Engagement + retention | Quality multiplier |
| Cross-app adoption | Ecosystem multiplier |

> **Value created for the network → rewards returned to the creator.**

---

## The Partner Reward Formula

> **More verified active users + better retention = larger share of protocol rewards.**

### Reward Distribution (Per Epoch)

An **epoch** is a fixed accounting period (e.g., monthly or quarterly).

$$
\text{Reward}_i(t) = \text{Pool}(t) \times \frac{\text{Score}_i(t)}{\sum_j \text{Score}_j(t)}
$$

Where:
- **Pool(t)** = total CDO allocated for partner rewards in epoch *t*  
  *(governance-defined; may be funded by emissions, protocol revenue, and/or DAO treasury)*
- **Score_i(t)** = partner *i* contribution score
- **Σ Score_j(t)** = normalization across all partners

### Contribution Score

$$
\text{Score}_i = w_u \cdot f(\text{MAU}_i) + w_r \cdot \text{Retention}_{30} + w_x \cdot \text{CrossAppActivation} - w_s \cdot \text{SybilRisk}
$$

**Constraints:**
- All weights are non-negative: $w_k \geq 0$
- Weights sum to one: $w_u + w_r + w_x + w_s = 1$
- Weights and metrics are governance-defined and may evolve

**Definitions:**
- **MAU** = Monthly Active Users (verified, anti-bot)
- **Retention₃₀** = % still active after 30 days
- **CrossAppActivation** = users who adopt other Zero Fee apps
- **SybilRisk** = anti-fraud penalty (prevents "fake users" gaming)

### Fairness Function (Prevents Monopoly Capture)

To reduce runaway concentration, MAU is scored with a **concave function**:

$$
f(\text{MAU}) = \log(1 + \text{MAU})
$$

Large apps still win, but not infinitely — smaller high-quality apps remain competitive.

### Illustrative Example (Not a Promise)

| Partner | MAU | Retention | Pool Share |
|---------|-----|-----------|------------|
| Small app | 500 | 85% | ~2% |
| Medium app | 5,000 | 70% | ~10% |
| Large app | 50,000 | 60% | ~25% |

---

## Integrity & Anti-Gaming (Privacy-Preserving)

The protocol rewards **real users**, not bots.

| Protection | Implementation |
|------------|----------------|
| **Sybil resistance** | On-chain reputation / attestations (optional, jurisdiction-dependent) |
| **Bot prevention** | Rate limits, anomaly detection, challenge-response flows |
| **Fake user penalties** | SybilRisk reduces score and reward share |
| **Auditability** | Verifiable aggregates (minimum necessary data; privacy-first) |

Partners who attempt manipulation may face:
- Reward suspension
- Reputation penalties
- Removal from the program (governance-defined)

---

## Partner Commitments

| You Commit | You Receive |
|------------|-------------|
| Hold $1,000+ CDO (alignment bond) | Access to app factory pipeline + community execution |
| Operate Zero Fee (no platform cuts) | Share of protocol reward pools |
| Onboard users into Infinite Package | Growth-aligned reward multipliers |
| Introduce partner candidates (optional) | Ecosystem expansion bonuses (governance-defined) |

> **Partner introductions are an ecosystem growth mechanism — not a compensation scheme.**

---

## Infinite Package for Users

Users enter through:

| Package | Cost | What it unlocks |
|---------|------|-----------------|
| **Infinite** | $100 CDO | Unlimited zero-fee access to participating Candao apps |

### Token Lock Schedule

User tokens are locked with gradual unlock (same as partners):

| Year | Unlock | Cumulative |
|------|--------|------------|
| 1 | 0% | 0% liquid |
| 2 | 10% | 10% liquid |
| 3 | 10% | 20% liquid |
| 4 | 40% | 60% liquid |
| 5 | 40% | 100% liquid |

> **Your access never stops.** The lock removes tokens from circulation, creating healthier tokenomics. You keep your tokens — they just become liquid gradually.

**Note:** Infinite Package excludes external hard costs:
- Heavy AI compute
- Payment rail fees
- Shipping / logistics
- Third-party services

Users aren't buying access to one app.  
They're buying access to an **expanding universe of Zero Fee apps**.

---

## The Partner Flywheel

```
┌─────────────────────────────────────────────────────────┐
│                   PARTNER FLYWHEEL                       │
├─────────────────────────────────────────────────────────┤
│                                                          │
│    Partner commits $1,000+ CDO                           │
│              ↓                                           │
│    Gets app built by 360° Community                      │
│              ↓                                           │
│    Operates Zero Fee → attracts users                    │
│              ↓                                           │
│    Users buy Infinite Package ($100 CDO)                 │
│              ↓                                           │
│    CDO demand increases → Partner rewards grow           │
│              ↓                                           │
│    [Repeat]                                              │
│                                                          │
└─────────────────────────────────────────────────────────┘
```

---

## Important Disclaimers

> ⚠️ **Not investment advice.**
>
> - Reward pools and scoring rules are governance-defined and may change
> - Token prices fluctuate; there are no guarantees
> - Examples are illustrative only
> - Partners earn via protocol participation and direct business value — not price promises

---

## Summary

**Convert your app to Zero Fee.**  
**Commit $1,000+ in CDO as alignment.**  
**Grow real users and retention.**  
**Earn via protocol rewards and direct revenue — not by taxing your community.**

The whole system grows as a movement: **no rent extraction, ownership, contribution, rewards.**
