# Daniel Alves

### Security Researcher · Web3 · Blockchain Infrastructure · DeFi · Web2

Independent security researcher focused on high impact vulnerabilities across smart contracts, DeFi, cross chain systems, blockchain infrastructure, governance, and Web2. My work emphasizes reproducible proofs of concept, real protocol paths, and publicly verifiable evidence.

[![GitHub](https://img.shields.io/badge/GitHub-f00dat-181717?style=for-the-badge&logo=github)](https://github.com/f00dat)
[![DEV](https://img.shields.io/badge/DEV-Technical_Writeups-0A0A0A?style=for-the-badge&logo=devdotto)](https://dev.to/f00dat)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Daniel_Alves-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/danielalvesads/)

![Web3 Security](https://img.shields.io/badge/Web3-Security-6f42c1?style=flat-square)
![Blockchain Security](https://img.shields.io/badge/Blockchain-Security-7c3aed?style=flat-square)
![DeFi Security](https://img.shields.io/badge/DeFi-Security-f59e0b?style=flat-square)
![Smart Contract Auditing](https://img.shields.io/badge/Smart_Contracts-Auditing-2ea44f?style=flat-square)
![Web2 Research](https://img.shields.io/badge/Web2-Vulnerability_Research-2563eb?style=flat-square)
![Public CVE](https://img.shields.io/badge/Public_CVE-1-b91c1c?style=flat-square)

**Primary research handle:** `f00dat`  
**Code4rena credit:** `I1iveF0rTh1Sh1t`

## Navigation

[Selected Impact](#selected-impact) · [Featured Research](#featured-research) · [Audit Contests](#audit-contest-research) · [Bug Bounties](#web3-bug-bounty-research) · [Public CVE](#public-cve) · [Research Focus](#research-focus) · [Research Standard](#research-standard) · [Contact](#contact)

## Selected Impact

| Result | Public evidence |
|---|---|
| **29 validated findings** across public contests and bug bounty programs | [Audit contests](#audit-contest-research) · [Bug bounties](#web3-bug-bounty-research) |
| **2 Critical findings** in cross chain and token wrapper systems | [ZIGChain](https://hackenproof.com/reports/ZIGCHDD-74) · [Overlayer](https://hackenproof.com/reports/OVLRSCDD-30) |
| **11 High findings** across DeFi, smart contracts, and protocol accounting | [Featured research](#featured-research) |
| **1 public CVE** in Apache Log4net | [Apache Advisory](https://logging.apache.org/security.html#CVE-2026-40021) · [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-40021) |
| **29 public technical writeups** with reproduction paths and impact analysis | [DEV](https://dev.to/f00dat) |
| **10 valid WEMIX reports** spanning consensus, governance, staking, P2P, DeFi, and reserve accounting | [WEMIX research](#certik-skynet--wemix) |
| **9 validated 0xMarkets findings** across oracle, vault, execution-fee, share-accounting, and redemption paths | [0xMarkets research](#hackenproof--0xmarkets) |

## Overview

| Validated Findings | Rewarded Findings | Technical Writeups | Public CVE |
|---:|---:|---:|---:|
| **29** | **28** | **29** | **1** |

| Critical | High | Medium | Low |
|---:|---:|---:|---:|
| **2** | **11** | **6** | **10** |

| Category | Valid | Rewarded | Writeups |
|---|---:|---:|---:|
| Audit contests | 18 | 17 | 18 |
| Web3 bug bounties | 11 | 11 | 11 |
| **Combined** | **29** | **28** | **29** |

> Final severities reflect the official classification assigned by each contest, program, or vendor. Private, pending, rejected, and embargoed reports are not included.


## Featured Research

| Project | Finding | Severity | Evidence |
|---|---|---:|---|
| **ZIGChain** | Untrusted IBC voucher collision drained native token wrapper reserves | **Critical** | [Article](https://dev.to/f00dat/how-a-base-denom-collision-let-untrusted-ibc-vouchers-drain-zigchains-native-reserves-3o5j) · [Report](https://hackenproof.com/reports/ZIGCHDD-74) |
| **Overlayer** | Destination local counter underflow stranded first inbound transfers | **Critical** | [Article](https://dev.to/f00dat/how-overlayers-destination-local-counter-permanently-stranded-first-inbound-transfers-7i7) · [Report](https://hackenproof.com/reports/OVLRSCDD-30) |
| **Panoptic** | Reinitializable `BuilderWallet` enabled admin replacement and fee theft | **High** | [Article](https://dev.to/f00dat/how-a-reinitializable-builderwallet-let-anyone-steal-builder-fees-586d) · [Final Report](https://code4rena.com/reports/2025-12-panoptic-next-core#h-01-builderwallet-init-is-unprotectedre-initializable-enabling-takeover-and-theft-of-builder-fees) |
| **0xMarkets** | Stale GLV share pricing captured pending insurance recapitalization | **High** | [Article](https://dev.to/f00dat/how-stale-glv-share-pricing-allowed-new-depositors-to-capture-pending-insurance-recapitalization-5fn6) |
| **0xMarkets** | Permissionless Pyth Lazer calls drained provider-funded verification fees and broke price updates | **Medium** | [Article](https://dev.to/f00dat/how-permissionless-pyth-lazer-calls-could-drain-0xmarkets-oracle-fee-balance-and-break-price-5kd) |
| **0xMarkets** | Successful request executions orphaned users’ WNT execution fees across five production paths | **High** | [Article](https://dev.to/f00dat/how-successful-0xmarkets-requests-could-permanently-orphan-users-wnt-execution-fees-2hcg) |
| **0xMarkets** | Transaction-scoped Oracle prices froze CarthaVault accounting after GM settlement | **High** | [Article](https://dev.to/f00dat/how-transaction-scoped-0xmarkets-oracle-prices-could-freeze-carthavault-after-gm-settlement-1n1c) |
| **WEMIX** | Removed validator remained accepted as signer and reward recipient | **Medium** | [Article](https://dev.to/f00dat/how-wemix-kept-accepting-a-removed-validator-as-an-active-signer-1135) · [Report](https://gist.github.com/f00dat/96219a676da64aeef5eadf174cb0b442) |
| **Apache Log4net** | XML 1.0 forbidden characters could silently suppress log records | **Medium** | [Apache Advisory](https://logging.apache.org/security.html#CVE-2026-40021) · [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-40021) |

### Detailed Public Record

| Category | Valid | Rewarded | Writeups | Documented Rewards |
|---|---:|---:|---:|---:|
| Audit contests | 18 | 17 | 18 | $1,199.64 |
| Web3 bug bounties | 11 | 11 | 11 | $1,500.00 |
| **Combined** | **29** | **28** | **29** | **$2,699.64** |

> Reward amounts are preserved here for transparency, but they are not used as headline indicators of technical impact.

# Audit Contest Research

## HackenProof · 0xMarkets

**9 validated findings · 7 High · 2 Medium · $435.28**

| # | Finding | Severity | Reward | Writeup |
|---:|---|---:|---:|---|
| 1 | Stale GLV share pricing captured pending insurance recapitalization | High | $343.64 | [Read](https://dev.to/f00dat/how-stale-glv-share-pricing-allowed-new-depositors-to-capture-pending-insurance-recapitalization-5fn6) |
| 2 | WNT collateral orders reimbursed an execution fee already funded by the main account | High | $60.87 | [Read](https://dev.to/f00dat/how-wnt-collateral-orders-let-subaccounts-claim-execution-fees-they-never-paid-5241) |
| 3 | Pending request value enabled CarthaVault share inflation | High | $27.65 | [Read](https://dev.to/f00dat/how-pending-0xmarkets-requests-enabled-share-inflation-in-carthavault-5352) |
| 4 | Wrong WNT receiver broke nonzero execution-fee paths | Medium | Included in total | [Read](https://dev.to/f00dat/how-a-wrong-wnt-receiver-broke-carthavaults-nonzero-execution-fee-paths-4156) |
| 5 | Transferred shares became permanently unredeemable after the original Position was deleted | High | Included in total | [Read](https://dev.to/f00dat/how-transferred-carthavault-shares-became-permanently-unredeemable-133n) |
| 6 | A `1e12` GM decimal mismatch let existing LPs capture later deposits | High | Included in total | [Read](https://dev.to/f00dat/how-a-1e12-decimal-mismatch-let-existing-lps-capture-later-deposits-57fm) |
| 7 | Permissionless Pyth Lazer oracle calls could drain the provider ETH balance and break legitimate price updates | Medium | Included in total | [Read](https://dev.to/f00dat/how-permissionless-pyth-lazer-calls-could-drain-0xmarkets-oracle-fee-balance-and-break-price-5kd) |
| 8 | Successful request executions permanently orphan users’ WNT execution fees because execution fee payout is disabled | High | Included in total | [Read](https://dev.to/f00dat/how-successful-0xmarkets-requests-could-permanently-orphan-users-wnt-execution-fees-2hcg) |
| 9 | Transaction-scoped 0xMarkets Oracle primary prices freeze CarthaVault deposits and withdrawals after GM settlement | High | Included in total | [Read](https://dev.to/f00dat/how-transaction-scoped-0xmarkets-oracle-prices-could-freeze-carthavault-after-gm-settlement-1n1c) |

> The contest total is preserved above. The latest publicly documented 0xMarkets findings include small individual pool allocations such as $0.52 for the CarthaVault Oracle-lifetime issue. Other very small allocations remain grouped into the contest total so the table emphasizes validated technical impact rather than payout mechanics.

---

## HackenProof · Overlayer DualDefense

**1 Critical · $68.97**

| Finding | Severity | Reward | Public Evidence |
|---|---:|---:|---|
| Destination-local `totalBridgedOut` underflow permanently stranded first inbound transfers | Critical | $68.97 | [Article](https://dev.to/f00dat/how-overlayers-destination-local-counter-permanently-stranded-first-inbound-transfers-7i7) · [Report](https://hackenproof.com/reports/OVLRSCDD-30) |

---

## HackenProof · ZIGChain Code DualDefense

**1 Critical · $443.00**

| Finding | Severity | Reward | Public Evidence |
|---|---:|---:|---|
| Base-denom-only validation let untrusted IBC vouchers drain native token wrapper reserves | Critical | $443.00 | [Article](https://dev.to/f00dat/how-a-base-denom-collision-let-untrusted-ibc-vouchers-drain-zigchains-native-reserves-3o5j) · [Report](https://hackenproof.com/reports/ZIGCHDD-74) |

---

## Code4rena · Panoptic: Next Core

**1 High · Published as H-01**

| Finding | Severity | Reward | Public Evidence |
|---|---:|---:|---|
| Reinitializable `BuilderWallet` let anyone replace the admin and steal builder fee balances | High | No payout | [Article](https://dev.to/f00dat/how-a-reinitializable-builderwallet-let-anyone-steal-builder-fees-586d) · [Final Report](https://code4rena.com/reports/2025-12-panoptic-next-core#h-01-builderwallet-init-is-unprotectedre-initializable-enabling-takeover-and-theft-of-builder-fees) |

> Code4rena credited `I1iveF0rTh1Sh1t` among the researchers who identified the final High finding.

---

## Code4rena · Rujira

**25th place · 3 High · 3 Medium · $252.39**

| # | Finding | Severity | Public Evidence |
|---:|---|---:|---|
| 1 | Borrow limit bypass through share rounding and floored ownership accounting | Medium | [Article](https://dev.to/f00dat/how-share-rounding-let-a-rujira-borrower-take-2-tokens-with-a-limit-of-1-22h9) · [Results](https://code4rena.com/audits/2025-12-rujira) |
| 2 | `adjusted_ltv()` division by zero could DoS queries and liquidation checks | Medium | [Article](https://dev.to/f00dat/how-zero-adjusted-collateral-could-dos-rujira-credit-queries-and-liquidations-1ipa) · [Results](https://code4rena.com/audits/2025-12-rujira) |
| 3 | Repay clamping and rounding could create permanent dust debt | Medium | [Article](https://dev.to/f00dat/how-repay-clamping-created-permanent-dust-debt-in-rujira-ghost-vault-53fh) · [Results](https://code4rena.com/audits/2025-12-rujira) |
| 4 | Invalid borrower-controlled `LiquidateMsg::Repay` preference could brick liquidation | High | [Article](https://dev.to/f00dat/how-a-borrower-controlled-repay-preference-could-brick-rujira-liquidations-552j) · [Results](https://code4rena.com/audits/2025-12-rujira) |
| 5 | Liquidator could extract a hidden bonus up to `liquidation_max_slip` | High | [Article](https://dev.to/f00dat/how-rujiras-slippage-guard-could-become-a-hidden-liquidation-bonus-58j4) · [Results](https://code4rena.com/audits/2025-12-rujira) |
| 6 | Unbounded borrower `preference_msgs` could make liquidation economically unexecutable | High | [Article](https://dev.to/f00dat/how-unbounded-borrower-preferences-could-make-rujira-liquidations-economically-impossible-4cf5) · [Results](https://code4rena.com/audits/2025-12-rujira) |

---

## Audit Contest Summary

| Critical | High | Medium | Valid | Rewarded | Rewards |
|---:|---:|---:|---:|---:|---:|
| **2** | **11** | **5** | **18** | **17** | **$1,199.64** |

---

# Web3 Bug Bounty Research

## CertiK Skynet · WEMIX

### 10 Valid Reports · 10 Rewards · 10 Public Articles · $1,400.00

![WEMIX Medium](https://img.shields.io/badge/Final_Medium-1-f59e0b?style=flat-square)
![WEMIX Low](https://img.shields.io/badge/Final_Low-9-2563eb?style=flat-square)

| # | Finding | Submitted | Final | Reward | Evidence |
|---:|---|---:|---:|---:|---|
| 1 | Removed validator remained accepted as signer and reward recipient after validator-index corruption | Critical | Medium | $500.00 | [Article](https://dev.to/f00dat/how-wemix-kept-accepting-a-removed-validator-as-an-active-signer-1135) · [Report](https://gist.github.com/f00dat/96219a676da64aeef5eadf174cb0b442) |
| 2 | Arbitrary ERC20 input drained native WEMIX through the WWEMIX shortcut and minted LP to the attacker | Major | Low | $100.00 | [Article](https://dev.to/f00dat/how-an-arbitrary-erc20-drained-native-wemix-from-weswapzapin-5h71) · [Report](https://gist.github.com/f00dat/031f9b602bc032233ae69eb0857ed305) |
| 3 | SPoA signatures failed to authenticate consensus-critical header fields | Major | Low | $100.00 | [Article](https://dev.to/f00dat/how-wemix-spoa-accepted-mutated-block-headers-under-an-unchanged-validator-signature-1n92) · [Report](https://gist.github.com/f00dat/ac7c36050f6cd632b31503667d2fe666) |
| 4 | Candidate block validation read canonical governance by height, making reorg validation branch-dependent | Major | Low | $100.00 | [Article](https://dev.to/f00dat/how-canonical-governance-reads-made-wemix-spoa-reorg-validation-branch-dependent-354j) · [Report](https://gist.github.com/f00dat/f4e3e1051726904c98888fca8130a8d2) |
| 5 | A second NCP exit overwrote unclaimed user and administrator withdrawal reserves | Major | Low | $100.00 | [Article](https://dev.to/f00dat/how-a-second-ncp-exit-orphaned-unclaimed-withdrawal-reserves-in-wemix-18k0) · [Report](https://gist.github.com/f00dat/48ca142692c2a9379ceb302856eefa9a) |
| 6 | NCP removal skipped the delegated exit path and froze user reserves | Major | Low | $100.00 | [Article](https://dev.to/f00dat/how-wemix-ncp-removal-skipped-the-exit-path-and-froze-delegated-reserves-oh8) · [Report](https://gist.github.com/f00dat/2046feb0f33bd610e1dd8023e441f180) |
| 7 | Unsigned `TransactionEx.From` metadata poisoned sender recovery and created state-root divergence | Major | Low | $100.00 | [Article](https://dev.to/f00dat/how-unsigned-partner-metadata-could-make-wemix-block-producers-build-invalid-blocks-17fn) · [Report](https://gist.github.com/f00dat/336c1b0ee5ce029b4e8569a8fae024e4) |
| 8 | Unsolicited `EtcdCluster` packets could stall or redirect mining coordination | Major | Low | $100.00 | [Article](https://dev.to/f00dat/how-unsolicited-etcdcluster-packets-could-stall-or-redirect-wemix-mining-coordination-fn0) · [Report](https://gist.github.com/f00dat/61da5d2e573db3387876bb50b14a66c7) |
| 9 | Raising `minStaking` made an existing NCP unable to participate and unremovable | Major | Low | $100.00 | [Article](https://dev.to/f00dat/how-a-minstaking-increase-could-make-an-understaked-wemix-ncp-unremovable-4je5) · [Report](https://gist.github.com/f00dat/c639b85236f38a6916f8367d40aba766) |
| 10 | Integer-truncated vote weights blocked governance voting for seven days | Major | Low | $100.00 | [Article](https://dev.to/f00dat/how-integer-truncated-vote-weights-could-lock-wemix-governance-for-seven-days-2efp) · [Report](https://gist.github.com/f00dat/e159e3b949537e59839e667ebbe7f82e) |

### WEMIX Coverage

| Area | Findings | Main Themes |
|---|---:|---|
| Governance and staking | 4 | Membership integrity, exit lifecycle, voting arithmetic, liveness |
| Consensus and validation | 2 | Signature scope, branch-dependent state |
| P2P and mining coordination | 2 | Sender recovery, request correlation |
| DeFi and custodial flows | 1 | Native token extraction and LP minting |
| Exit reserve accounting | 1 | Reserve overwrite and stranded withdrawals |

### Severity Classification Record

| Submitted | Final | Count | Rewards |
|---|---|---:|---:|
| Critical | Medium | 1 | $500.00 |
| Major | Low | 9 | $900.00 |
| **Total** | **1 Medium · 9 Low** | **10** | **$1,400.00** |

> All ten WEMIX reports were accepted as valid, publicly documented, and rewarded. Nine reports submitted as Major were finalized as Low. The public writeups preserve the complete reproduction paths, demonstrated impacts, limitations, and technical basis for the submitted severities. This documents the recurring pattern of systematic downgrading across these submissions without claiming a motive for individual decisions.

### Latest governance finding at a glance

```text
Eligible members
6

Votes cast
6

Recorded voting power
9996

Ballot finalized
No

Other proposal votable
No

Maximum lock duration
7 days
```

The fully participated ballot remained active because integer-truncated weights could never reach the exact `10000` fallback. Since `ballotInVoting` was still occupied, another valid emergency proposal remained blocked until timeout cleanup.


---

## HackenProof · Momentum

**1 Low**

| Finding | Submitted | Final | Reward | Evidence |
|---|---:|---:|---:|---|
| Zero-liquidity `flash_swap` crossed initialized ticks for free, mutated oracle state, and could stall reward claimability | High | Low | $100.00 | [Article](https://dev.to/f00dat/how-a-zero-liquidity-flash-swap-crossed-momentum-ticks-for-free-and-stalled-rewards-4369) |

---

## Web3 Bug Bounty Summary

| Medium | Low | Valid | Rewarded | Writeups | Rewards |
|---:|---:|---:|---:|---:|---:|
| **1** | **10** | **11** | **11** | **11** | **$1,500.00** |

---

## Public CVE

### CVE 2026 40021 · Apache Log4net

#### Silent loss of log events in `XmlLayout` and `XmlLayoutSchemaLog4J` caused by unescaped XML 1.0 forbidden characters

| Field | Details |
|---|---|
| Product | Apache Log4net |
| Vendor severity | Medium |
| CVSS 4.0 | 6.3 |
| Affected versions | Before 3.3.0 |
| Fixed version | 3.3.0 |
| Research credit | `f00dat` |
| Disclosure platform | YesWeHack |

Attacker influenced MDC property keys, MDC values, and identity data could introduce XML 1.0 forbidden characters. The resulting serialization exception could silently suppress individual log records, weakening audit trails and malicious activity detection.

[Apache Advisory](https://logging.apache.org/security.html#CVE-2026-40021) · [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-40021) · [GitHub Advisory](https://github.com/advisories/GHSA-4f7c-pmjv-c25w) · [Fix Pull Request](https://github.com/apache/logging-log4net/pull/280) · [oss security](https://www.openwall.com/lists/oss-security/2026/04/10/11)

## Research Focus

### Smart Contracts and DeFi
Authorization, state transitions, share pricing, dilution, settlement, recapitalization, asset ownership, and economic invariants.

### Cross Chain Systems
Message validation, replay protection, destination binding, distributed accounting, bridge invariants, and token wrapper trust boundaries.

### Blockchain Infrastructure
Consensus, block validation, signer identity, node behavior, P2P protocols, mining coordination, and reorg safety.

### Governance Systems
Voting arithmetic, membership integrity, proposal lifecycle, staking transitions, cleanup safety, and emergency liveness.

### Web2 Security
Application security, logging integrity, parser behavior, and coordinated vulnerability disclosure.

### Proof Development
Reproducible end to end proofs using real protocol paths whenever possible, with explicit controls, measurable state transitions, and bounded impact claims.

## Research Standard

Only findings meeting at least one of these conditions are included:

1. Officially validated by a bug bounty program
2. Accepted in a public audit contest
3. Confirmed as a duplicate of a valid issue
4. Assigned a public CVE
5. Supported by public evidence after disclosure is permitted

Private, pending, rejected, and embargoed reports are excluded.

## Contact

[![GitHub](https://img.shields.io/badge/GitHub-f00dat-181717?style=for-the-badge&logo=github)](https://github.com/f00dat)
[![DEV](https://img.shields.io/badge/DEV-Technical_Writeups-0A0A0A?style=for-the-badge&logo=devdotto)](https://dev.to/f00dat)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Daniel_Alves-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/danielalvesads/)
