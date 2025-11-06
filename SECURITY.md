# Security & Verification Disclosure

## On‑Chain Data
- **Network:** Solana (SPL)
- **Token Address:** `EmHzo9nRsFBwkU7tB5S3QAFhLpVPEWNqxQ4qrPfutmuH`
- **Total Supply (on-chain):** 13,500,000,000 MAC  
- **Owner Wallet:** `3XmAHVMV5HZ2GNMBt5z5hYNo8H4yaGMXkt1HzcCwg8Fe`
- **Contract Creation:** 2025‑04‑08 *(verified via De.Fi & Solscan)*

---

## Current Risk Posture *(as of November 2025)*
| Parameter | Status | Source |
|------------|--------|--------|
| **Liquidity Pool** | ❌ None Detected | De.Fi Scanner |
| **Holder Concentration** | ⚠️ High (~99.878% in one wallet) | De.Fi |
| **De.Fi Safety Score** | 36–37 / 100 | De.Fi Scanner |
| **Audit Report** | Pending | To be published in `/AUDIT` |
| **Team KYC** | Pending | To be published in `/KYC` |

---

## Action Plan
### 1. Liquidity & Lock
- Initial liquidity will be added and locked via **PinkLock** or **RugLock** immediately after completion of the presale (Phase I).
- Lock transaction details will be published publicly on Solscan and in the `/AUDIT/liquidity-lock.json` file.

### 2. Token Distribution
- Gradual distribution from owner wallet to **presale buyers**, **team vesting**, and **ecosystem incentives**.
- Schedule and percentage allocations will be tracked in `/distribution-plan.md`.

### 3. Security Verification
- Free automated scans completed via:
  - [De.Fi Scanner](https://de.fi/scanner/contract/EmHzo9nRsFBwkU7tB5S3QAFhLpVPEWNqxQ4qrPfutmuH?chainId=sol)
  - [GoPlus Security](https://gopluslabs.io)
- Next step: obtain **manual audit** from *SolidProof* or *TechRate* (PDF to be added in `/AUDIT`).

### 4. KYC Verification
- Project team will complete KYC verification through *AssureDeFi*, *Coinscope*, or *CoinSniper Community KYC*.
- Certificate and verification ID will be attached under `/KYC/` once issued.

### 5. Transparency Commitment
- All public repositories and website sections (`/security`, `/docs`, `/presale`) will remain in sync with this file.
- Any change in total supply, decimals, or ownership will be immediately disclosed with commit references.

---

## Contact
- 🔐 **Security Inquiries:** [security@maccoin.app](mailto:security@maccoin.app)  
- 📧 **Official Contact:** [info@maccoin.app](mailto:info@maccoin.app)  
- 🌐 Website: [https://maccoin.app](https://maccoin.app)

---

## Branding Consistency
**Project Name:** MarketCoin  
**Ticker Symbol:** MAC  
*(Note: the Presale UI currently references “MCoin”; this will be updated to “MAC” for naming consistency.)*

---

### Statement of Integrity
MarketCoin commits to operate with transparency and accountability.  
All audits, liquidity locks, and ownership verifications will be publicly verifiable on‑chain via Solscan and documented in this repository.
