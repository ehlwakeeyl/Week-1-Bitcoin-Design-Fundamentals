# Wallet Type Differences (Strike vs BlueWallet vs Zeus)

## Compared Wallets
- Strike
- BlueWallet
- Zeus Wallet

---

# 1. High-Level Categorization

| Wallet | Custody Model | Lightning Support | Node Control | User Level |
|---------|--------------|------------------|--------------|------------|
| Strike | Custodial | Yes | No | Beginner |
| BlueWallet | Hybrid | Yes | Optional | Intermediate |
| Zeus | Non-Custodial | Yes (Native) | Yes | Advanced |

---

# 2. Strike — Custodial Lightning Wallet

## Category
Custodial Wallet (Lightning-first fintech model)

## Key Characteristics
- Company holds private keys
- Login via phone/email
- 2FA enforced
- KYC required
- Bitcoin complexity abstracted

## Lightning Role
- Lightning is invisible to the user
- Payments feel like standard app transfers

## Designed For
- Mass adoption
- Non-technical users
- Convenience-first users

## Philosophy
Bitcoin made invisible

---

# 3. BlueWallet — Hybrid Self-Custody Wallet

## Category
Non-Custodial (On-chain) + Optional Custodial Lightning

## Key Characteristics
- User controls seed phrase (on-chain wallets)
- Lightning can be custodial unless connected to own node
- Manual wallet management
- Fee customization available

## Lightning Role
- Separate wallet type
- Requires some understanding

## Designed For
- Users transitioning to self-custody
- Intermediate Bitcoin users
- Users learning Bitcoin mechanics

## Philosophy
Self-custody made accessible

---

# 4. Zeus — Non-Custodial Node-Control Wallet

## Category
Non-Custodial Lightning Node Controller

## Key Characteristics
- Connects to your own Lightning node
- Full channel management
- Liquidity management
- Routing visibility
- Minimal abstraction

## Lightning Role
- Core infrastructure layer
- User manages channels and sync

## Designed For
- Node operators
- Developers
- Advanced Lightning users

## Philosophy
Maximum sovereignty and control

---

# 5. Core Differences

## A. Custody Responsibility

- Strike → Company responsible
- BlueWallet → User responsible (on-chain)
- Zeus → User responsible + infrastructure management

---

## B. Complexity Level

- Strike → Simplified
- BlueWallet → Transparent
- Zeus → Technical

---

## C. Bitcoin Abstraction Level

- Strike → High abstraction (hides complexity)
- BlueWallet → Moderate abstraction
- Zeus → Minimal abstraction

---

## D. User Decision Load at Entry

- Strike → Low (Login/Signup)
- BlueWallet → Medium (Choose wallet type)
- Zeus → High (Multiple setup paths)

---

# 6. User Maturity Model

A typical progression path:

1. Start with Strike (ease & adoption)
2. Move to BlueWallet (self-custody awareness)
3. Graduate to Zeus (Lightning infrastructure control)

Each wallet reflects increasing levels of:

- Technical depth
- Responsibility
- Decentralization alignment