# Daniel Alves

### Security Researcher · Web3 · Web2 · Smart Contracts · Blockchain Infrastructure · DeFi

## Professional Summary

Security Researcher focused on vulnerability research across Web3 and Web2, including smart contracts, DeFi, cross-chain systems, blockchain infrastructure, application security, logging integrity, parser behavior, and coordinated vulnerability disclosure.

Public research record includes 34 validated findings across audit contests and bug bounty programs, 2 final Critical findings, 12 final High findings, 34 public technical writeups, and 1 public CVE in Apache Log4net.

My work emphasizes reproducible proofs of concept, real protocol paths, measurable state transitions, explicit control cases, and publicly verifiable evidence.

[![GitHub](https://img.shields.io/badge/GitHub-f00dat-181717?style=for-the-badge&logo=github)](https://github.com/f00dat)
[![DEV](https://img.shields.io/badge/DEV-Technical_Writeups-0A0A0A?style=for-the-badge&logo=devdotto)](https://dev.to/f00dat)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Daniel_Alves-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/danielalvesads/)

![Web3 Security](https://img.shields.io/badge/Web3-Security-6f42c1?style=flat-square)
![Blockchain Security](https://img.shields.io/badge/Blockchain-Security-7c3aed?style=flat-square)
![DeFi Security](https://img.shields.io/badge/DeFi-Security-f59e0b?style=flat-square)
![Smart Contract Auditing](https://img.shields.io/badge/Smart_Contracts-Auditing-2ea44f?style=flat-square)
![Web2 Research](https://img.shields.io/badge/Web2-Vulnerability_Research-2563eb?style=flat-square)
![Public CVE](https://img.shields.io/badge/Public_CVE-1-b91c1c?style=flat-square)

Primary research handle: `f00dat`  
Code4rena credit: `I1iveF0rTh1Sh1t`

---

## Portfolio Snapshot

![Validated Findings](https://img.shields.io/badge/Validated_Findings-34-2ea44f?style=for-the-badge)
![Critical Findings](https://img.shields.io/badge/Final_Critical-2-b91c1c?style=for-the-badge)
![High Findings](https://img.shields.io/badge/Final_High-12-e67e22?style=for-the-badge)
![Public CVE](https://img.shields.io/badge/Public_CVE-1-b91c1c?style=for-the-badge)
![Public Writeups](https://img.shields.io/badge/Public_Writeups-34-6f42c1?style=for-the-badge)

![Rewarded Findings](https://img.shields.io/badge/Rewarded_Findings-33-0A66C2?style=flat-square)
![Documented Rewards](https://img.shields.io/badge/Documented_Rewards-%243%2C136.92-f59e0b?style=flat-square)

### Final Severity Distribution

![Critical](https://img.shields.io/badge/Critical-2-b91c1c?style=flat-square)
![High](https://img.shields.io/badge/High-12-e67e22?style=flat-square)
![Medium](https://img.shields.io/badge/Medium-8-f59e0b?style=flat-square)
![Low](https://img.shields.io/badge/Low-12-2563eb?style=flat-square)

| Research Channel | Validated | Rewarded | Public Writeups | Documented Rewards |
|---|---:|---:|---:|---:|
| Audit contests | 21 | 20 | 21 | $1,418.12 |
| Web3 bug bounties | 13 | 13 | 13 | $1,718.80 |
| **Combined** | **34** | **33** | **34** | **$3,136.92** |

> Final severity totals use the official classification assigned by each contest, program, or vendor. Submitted severity is preserved separately where it is relevant to the public record. Private, pending, rejected, and embargoed reports are excluded.

### Key Public Records

| Record | Public Evidence |
|---|---|
| **2 final Critical findings** | [ZIGChain](https://hackenproof.com/reports/ZIGCHDD-74) · [Overlayer](https://hackenproof.com/reports/OVLRSCDD-30) |
| **10 valid WEMIX reports** across consensus, governance, staking, P2P, DeFi, and reserve accounting | [WEMIX research](#certik-skynet--wemix) |
| **9 validated 0xMarkets findings** across oracle, vault, execution-fee, share-accounting, and redemption paths | [0xMarkets research](#hackenproof--0xmarkets) |
| **1 public CVE** in Apache Log4net | [Apache Advisory](https://logging.apache.org/security.html#CVE-2026-40021) · [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-40021) |

---

## Core Expertise

| Domain | Focus |
|---|---|
| Smart Contract Security | Authorization, access control, state transitions, token accounting, settlement, economic invariants, and protocol liveness |
| DeFi Security | Share pricing, dilution, lending and liquidation logic, reward accounting, reserve accounting, oracle integrations, and execution flows |
| Cross-Chain Security | Message validation, replay protection, destination binding, bridge accounting, and token-wrapper trust boundaries |
| Blockchain Infrastructure | Consensus, block validation, signer identity, P2P behavior, mining coordination, governance, staking, and reorg safety |
| Web2 Application Security | Application behavior, attacker-controlled input handling, trust boundaries, failure modes, and vulnerability reproduction |
| Logging and Telemetry Security | Audit-trail integrity, log suppression, serialization failures, and security-monitoring reliability |
| Parser and Serialization Security | Parser behavior, malformed or forbidden input, encoding boundaries, and safe failure handling |
| Proof of Concept Development | Reproducible end-to-end PoCs using real protocol paths, explicit controls, measurable state transitions, and bounded impact claims |
| Coordinated Disclosure | Public technical documentation, vendor-facing reproduction evidence, CVE disclosure, and remediation-oriented reporting |

## Career Highlights

- 34 validated security findings across public audit contests and bug bounty programs.
- 2 final Critical and 12 final High findings across cross-chain, DeFi, smart contracts, and protocol infrastructure.
- 1 public Web2 CVE in Apache Log4net, credited to `f00dat`.
- 34 public technical writeups with reproducible evidence and impact analysis.
- Public research record across CertiK, HackenProof, Code4rena, Sherlock, and YesWeHack.
- Research spans both Web3 protocol security and Web2 application, logging, parser, and disclosure workflows.

---

## Navigation

[Snapshot](#portfolio-snapshot) · [Core Expertise](#core-expertise) · [Career Highlights](#career-highlights) · [Selected Research](#selected-research) · [Audit Contests](#audit-contest-research) · [Web3 Bug Bounties](#web3-bug-bounty-research) · [Web2 Security](#web2-security-research) · [Public CVE](#public-cve) · [Research Focus](#research-focus) · [Contact](#contact)

---

## Selected Research

A representative selection of publicly documented findings across smart contracts, protocol accounting, cross-chain systems, consensus, trading infrastructure, and Web2.

| Project | Finding | Severity Record | Public Evidence |
|---|---|---:|---|
| **ZIGChain** | Untrusted IBC voucher collision drained native token wrapper reserves | **Critical** | [Article](https://dev.to/f00dat/how-a-base-denom-collision-let-untrusted-ibc-vouchers-drain-zigchains-native-reserves-3o5j) · [Report](https://hackenproof.com/reports/ZIGCHDD-74) |
| **Overlayer** | Destination-local counter underflow stranded first inbound transfers | **Critical** | [Article](https://dev.to/f00dat/how-overlayers-destination-local-counter-permanently-stranded-first-inbound-transfers-7i7) · [Report](https://hackenproof.com/reports/OVLRSCDD-30) |
| **Panoptic** | Reinitializable `BuilderWallet` enabled admin replacement and builder-fee theft | **High** | [Article](https://dev.to/f00dat/how-a-reinitializable-builderwallet-let-anyone-steal-builder-fees-586d) · [Final Report](https://code4rena.com/reports/2025-12-panoptic-next-core#h-01-builderwallet-init-is-unprotectedre-initializable-enabling-takeover-and-theft-of-builder-fees) |
| **0xMarkets** | Stale GLV share pricing captured pending insurance recapitalization | **High** | [Article](https://dev.to/f00dat/how-stale-glv-share-pricing-allowed-new-depositors-to-capture-pending-insurance-recapitalization-5fn6) |
| **Fluid DEX V2** | Over-balance withdrawal debited a capped MoneyMarket position while forwarding the uncapped amount to pooled Liquidity | **High** | [Article](https://dev.to/f00dat/how-a-1-usdc-position-let-an-attacker-withdraw-800-usdc-from-fluid-moneymarkets-shared-liquidity-4pcn) · [Sherlock Submission](https://audits.sherlock.xyz/contests/1225/voting/860) |
| **CurrentSui** | Expired reward pool closure could refund borrower yield before lazy reward materialization | **High → Medium** | [Article](https://dev.to/f00dat/how-an-expired-currentsui-reward-pool-could-refund-yield-borrowers-had-already-earned-32aa) · [Sherlock Submission](https://audits.sherlock.xyz/contests/1256/voting/154) |
| **CurrentSui** | Double subtraction of `cash_reserve` reopened full markets and diverted active liquidity-mining rewards | **Medium** | [Article](https://dev.to/f00dat/how-double-subtracting-cashreserve-reopened-full-currentsui-markets-and-diverted-liquidity-mining-160m) · [Sherlock Submission](https://audits.sherlock.xyz/contests/1256/voting/244) |
| **CROSS** | Positive `offsetSeconds` restored mint capacity before the configured period ended, allowing `2 × LIMIT` inside one intended period | **Critical → Low** | [Article](https://dev.to/f00dat/how-a-positive-offsetseconds-bug-let-a-cross-forge-mint-2x-the-intended-erc20-period-limit-eon) · [Report](https://gist.github.com/f00dat/fe7084f0045a3e69434ad973ad2a21d2) |
| **CROSS** | Constructor-bypass maker order could repeatedly revert native CROSS pair matching through auto-unwrapped payouts | **Medium → Low** | [Article](https://dev.to/f00dat/how-a-constructor-bypass-let-malicious-cross-makers-block-native-pair-matching-3n64) · [Report](https://gist.github.com/f00dat/f4cd5aaaebc649999cb730606c31f17b) |
| **WEMIX** | Removed validator remained accepted as signer and reward recipient | **Critical → Medium** | [Article](https://dev.to/f00dat/how-wemix-kept-accepting-a-removed-validator-as-an-active-signer-1135) · [Report](https://gist.github.com/f00dat/96219a676da64aeef5eadf174cb0b442) |
| **Apache Log4net** | XML 1.0 forbidden characters could silently suppress log records | **Medium** | [Apache Advisory](https://logging.apache.org/security.html#CVE-2026-40021) · [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-40021) |

---

# Audit Contest Research

## HackenProof · 0xMarkets

![Validated](https://img.shields.io/badge/Validated-9-2ea44f?style=flat-square) ![High](https://img.shields.io/badge/High-7-e67e22?style=flat-square) ![Medium](https://img.shields.io/badge/Medium-2-f59e0b?style=flat-square) ![Rewards](https://img.shields.io/badge/Rewards-%24435.28-0A66C2?style=flat-square)

**9 validated findings · 7 High · 2 Medium · $435.28**

| # | Finding | Final Severity | Reward | Writeup |
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

![Critical](https://img.shields.io/badge/Critical-1-b91c1c?style=flat-square) ![Reward](https://img.shields.io/badge/Reward-%2468.97-0A66C2?style=flat-square)

**1 Critical · $68.97**

| Finding | Final Severity | Reward | Public Evidence |
|---|---:|---:|---|
| Destination-local `totalBridgedOut` underflow permanently stranded first inbound transfers | Critical | $68.97 | [Article](https://dev.to/f00dat/how-overlayers-destination-local-counter-permanently-stranded-first-inbound-transfers-7i7) · [Report](https://hackenproof.com/reports/OVLRSCDD-30) |

---

## HackenProof · ZIGChain Code DualDefense

![Critical](https://img.shields.io/badge/Critical-1-b91c1c?style=flat-square) ![Reward](https://img.shields.io/badge/Reward-%24443.00-0A66C2?style=flat-square)

**1 Critical · $443.00**

| Finding | Final Severity | Reward | Public Evidence |
|---|---:|---:|---|
| Base-denom-only validation let untrusted IBC vouchers drain native token wrapper reserves | Critical | $443.00 | [Article](https://dev.to/f00dat/how-a-base-denom-collision-let-untrusted-ibc-vouchers-drain-zigchains-native-reserves-3o5j) · [Report](https://hackenproof.com/reports/ZIGCHDD-74) |

---

## Code4rena · Panoptic: Next Core

![Final High](https://img.shields.io/badge/Final_High-H--01-e67e22?style=flat-square) ![Payout](https://img.shields.io/badge/Payout-No_Payout-6b7280?style=flat-square)

**1 High · Published as H-01**

| Finding | Final Severity | Reward | Public Evidence |
|---|---:|---:|---|
| Reinitializable `BuilderWallet` let anyone replace the admin and steal builder fee balances | High | No payout | [Article](https://dev.to/f00dat/how-a-reinitializable-builderwallet-let-anyone-steal-builder-fees-586d) · [Final Report](https://code4rena.com/reports/2025-12-panoptic-next-core#h-01-builderwallet-init-is-unprotectedre-initializable-enabling-takeover-and-theft-of-builder-fees) |

> Code4rena credited `I1iveF0rTh1Sh1t` among the researchers who identified the final High finding.

---

## Code4rena · Rujira

![Placement](https://img.shields.io/badge/Placement-25th-6f42c1?style=flat-square) ![High](https://img.shields.io/badge/High-3-e67e22?style=flat-square) ![Medium](https://img.shields.io/badge/Medium-3-f59e0b?style=flat-square) ![Rewards](https://img.shields.io/badge/Rewards-%24252.39-0A66C2?style=flat-square)

**25th place · 3 High · 3 Medium · $252.39**

| # | Finding | Final Severity | Public Evidence |
|---:|---|---:|---|
| 1 | Borrow limit bypass through share rounding and floored ownership accounting | Medium | [Article](https://dev.to/f00dat/how-share-rounding-let-a-rujira-borrower-take-2-tokens-with-a-limit-of-1-22h9) · [Results](https://code4rena.com/audits/2025-12-rujira) |
| 2 | `adjusted_ltv()` division by zero could DoS queries and liquidation checks | Medium | [Article](https://dev.to/f00dat/how-zero-adjusted-collateral-could-dos-rujira-credit-queries-and-liquidations-1ipa) · [Results](https://code4rena.com/audits/2025-12-rujira) |
| 3 | Repay clamping and rounding could create permanent dust debt | Medium | [Article](https://dev.to/f00dat/how-repay-clamping-created-permanent-dust-debt-in-rujira-ghost-vault-53fh) · [Results](https://code4rena.com/audits/2025-12-rujira) |
| 4 | Invalid borrower-controlled `LiquidateMsg::Repay` preference could brick liquidation | High | [Article](https://dev.to/f00dat/how-a-borrower-controlled-repay-preference-could-brick-rujira-liquidations-552j) · [Results](https://code4rena.com/audits/2025-12-rujira) |
| 5 | Liquidator could extract a hidden bonus up to `liquidation_max_slip` | High | [Article](https://dev.to/f00dat/how-rujiras-slippage-guard-could-become-a-hidden-liquidation-bonus-58j4) · [Results](https://code4rena.com/audits/2025-12-rujira) |
| 6 | Unbounded borrower `preference_msgs` could make liquidation economically unexecutable | High | [Article](https://dev.to/f00dat/how-unbounded-borrower-preferences-could-make-rujira-liquidations-economically-impossible-4cf5) · [Results](https://code4rena.com/audits/2025-12-rujira) |

---

## Sherlock · Fluid DEX V2

![High](https://img.shields.io/badge/High-1-e67e22?style=flat-square) ![Reward](https://img.shields.io/badge/Reward-%2434.00-0A66C2?style=flat-square)

**1 High · $34.00**

| Finding | Final Severity | Reward | Public Evidence |
|---|---:|---:|---|
| Normal supply withdrawal capped the MoneyMarket storage debit but forwarded the full requested amount to Liquidity, allowing withdrawal above balance from pooled funds | High | $34.00 | [Article](https://dev.to/f00dat/how-a-1-usdc-position-let-an-attacker-withdraw-800-usdc-from-fluid-moneymarkets-shared-liquidity-4pcn) · [Sherlock Submission](https://audits.sherlock.xyz/contests/1225/voting/860) |

---

## Sherlock · CurrentSui

![Final Medium](https://img.shields.io/badge/Final_Medium-2-f59e0b?style=flat-square) ![Rewards](https://img.shields.io/badge/Rewards-%24184.48-0A66C2?style=flat-square)

**2 Medium · $184.48**

| # | Finding | Submitted | Final | Reward | Public Evidence |
|---:|---|---:|---:|---:|---|
| 1 | Expired reward pool close could refund economically accrued borrower yield before lazy reward materialization | High | Medium | $92.24 | [Article](https://dev.to/f00dat/how-an-expired-currentsui-reward-pool-could-refund-yield-borrowers-had-already-earned-32aa) · [Sherlock Submission](https://audits.sherlock.xyz/contests/1256/voting/154) |
| 2 | Double subtraction of `cash_reserve` bypassed the deposit cap and diverted active liquidity mining rewards | Medium | Medium | $92.24 | [Article](https://dev.to/f00dat/how-double-subtracting-cashreserve-reopened-full-currentsui-markets-and-diverted-liquidity-mining-160m) · [Sherlock Submission](https://audits.sherlock.xyz/contests/1256/voting/244) |

---

## Audit Contest Summary

| Critical | High | Medium | Valid | Rewarded | Rewards |
|---:|---:|---:|---:|---:|---:|
| **2** | **12** | **7** | **21** | **20** | **$1,418.12** |

---

# Web3 Bug Bounty Research

## CertiK Skynet · WEMIX

![Valid Reports](https://img.shields.io/badge/Valid_Reports-10-2ea44f?style=flat-square) ![Rewarded](https://img.shields.io/badge/Rewarded-10-0A66C2?style=flat-square) ![Public Articles](https://img.shields.io/badge/Public_Articles-10-6f42c1?style=flat-square) ![Rewards](https://img.shields.io/badge/Rewards-%241%2C400.00-f59e0b?style=flat-square)

### 10 Valid Reports · 10 Rewards · 10 Public Articles · $1,400.00

![WEMIX Medium](https://img.shields.io/badge/Final_Medium-1-f59e0b?style=flat-square) ![WEMIX Low](https://img.shields.io/badge/Final_Low-9-2563eb?style=flat-square)

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

> All ten WEMIX reports were accepted as valid, publicly documented, and rewarded. Nine reports submitted as Major were finalized as Low. The public writeups preserve the complete reproduction paths, demonstrated impacts, limitations, and technical basis for the submitted severities. This records a recurring severity divergence across the submissions without assigning a motive to individual decisions.

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

![Final Low](https://img.shields.io/badge/Final_Low-1-2563eb?style=flat-square) ![Reward](https://img.shields.io/badge/Reward-%24100.00-0A66C2?style=flat-square)

**1 Low · $100.00**

| Finding | Submitted | Final | Reward | Evidence |
|---|---:|---:|---:|---|
| Zero-liquidity `flash_swap` crossed initialized ticks for free, mutated oracle state, and could stall reward claimability | High | Low | $100.00 | [Article](https://dev.to/f00dat/how-a-zero-liquidity-flash-swap-crossed-momentum-ticks-for-free-and-stalled-rewards-4369) |

---

## CertiK SkyShield · CROSS

![Valid Reports](https://img.shields.io/badge/Valid_Reports-2-2ea44f?style=flat-square) ![Rewarded](https://img.shields.io/badge/Rewarded-2-0A66C2?style=flat-square) ![Final Low](https://img.shields.io/badge/Final_Low-2-2563eb?style=flat-square) ![Rewards](https://img.shields.io/badge/Rewards-%24218.80-f59e0b?style=flat-square)

**2 valid reports · 2 rewards · $218.80**

| # | Finding | Submitted | Final | Reward | Evidence |
|---:|---|---:|---:|---:|---|
| 1 | Positive `offsetSeconds` prematurely reset `ERC20MintLimited` capacity, allowing a forge to mint `2 × LIMIT` before the configured period ended | Critical | Low | $109.40 | [Article](https://dev.to/f00dat/how-a-positive-offsetseconds-bug-let-a-cross-forge-mint-2x-the-intended-erc20-period-limit-eon) · [Public Report](https://gist.github.com/f00dat/fe7084f0045a3e69434ad973ad2a21d2) |
| 2 | Constructor-bypass maker order could repeatedly revert native CROSS pair matching by rejecting auto-unwrapped payouts | Medium | Low | $109.40 | [Article](https://dev.to/f00dat/how-a-constructor-bypass-let-malicious-cross-makers-block-native-pair-matching-3n64) · [Public Report](https://gist.github.com/f00dat/f4cd5aaaebc649999cb730606c31f17b) |

> Both findings were finalized as Low by CROSS. The public writeups preserve the technical basis for the submitted severities and document the severity disagreements, while the portfolio totals use the official final classifications.

---

## Web3 Bug Bounty Summary

| Medium | Low | Valid | Rewarded | Writeups | Rewards |
|---:|---:|---:|---:|---:|---:|
| **1** | **12** | **13** | **13** | **13** | **$1,718.80** |

---

# Web2 Security Research

Web2 research focuses on application security, logging and telemetry integrity, parser and serialization behavior, attacker-controlled input handling, safe failure modes, and coordinated vulnerability disclosure.

![Web2 Security](https://img.shields.io/badge/Web2-Security-2563eb?style=flat-square)
![Application Security](https://img.shields.io/badge/Application-Security-0A66C2?style=flat-square)
![Logging Integrity](https://img.shields.io/badge/Logging-Integrity-6f42c1?style=flat-square)
![Parser Security](https://img.shields.io/badge/Parser-Security-f59e0b?style=flat-square)
![Public CVE](https://img.shields.io/badge/Public_CVE-1-b91c1c?style=flat-square)

## Web2 Research Profile

| Area | Demonstrated Research Focus |
|---|---|
| Application Security | Vulnerability analysis across application behavior, input handling, trust boundaries, and failure conditions |
| Logging and Telemetry | Integrity of audit trails, log-record reliability, and failure modes that can weaken malicious-activity detection |
| Parser and Serialization | Forbidden-character handling, serialization exceptions, malformed input, and safe parser behavior |
| Security Controls | Reproducible tests that distinguish intended behavior from exploitable failure conditions |
| Coordinated Vulnerability Disclosure | Public advisory evidence, CVE tracking, remediation references, and vendor-facing technical documentation |

## Public CVE

### CVE-2026-40021 · Apache Log4net

![Vendor Severity](https://img.shields.io/badge/Vendor_Severity-Medium-f59e0b?style=flat-square) ![CVSS 4.0](https://img.shields.io/badge/CVSS_4.0-6.3-f59e0b?style=flat-square) ![Fixed](https://img.shields.io/badge/Fixed-3.3.0-2ea44f?style=flat-square)

### Silent loss of log events in `XmlLayout` and `XmlLayoutSchemaLog4J` caused by unescaped XML 1.0 forbidden characters

| Field | Details |
|---|---|
| Product | Apache Log4net |
| Vendor severity | Medium |
| CVSS 4.0 | 6.3 |
| Affected versions | Before 3.3.0 |
| Fixed version | 3.3.0 |
| Research credit | `f00dat` |
| Disclosure platform | YesWeHack |

Attacker-influenced MDC property keys, MDC values, and identity data could introduce XML 1.0 forbidden characters. The resulting serialization exception could silently suppress individual log records, weakening audit trails and malicious activity detection.

[Apache Advisory](https://logging.apache.org/security.html#CVE-2026-40021) · [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-40021) · [GitHub Advisory](https://github.com/advisories/GHSA-4f7c-pmjv-c25w) · [Fix Pull Request](https://github.com/apache/logging-log4net/pull/280) · [oss security](https://www.openwall.com/lists/oss-security/2026/04/10/11)

### Web2 Public Evidence Summary

| Record | Evidence |
|---|---|
| Public CVE | CVE-2026-40021 |
| Product | Apache Log4net |
| Vendor severity | Medium |
| CVSS 4.0 | 6.3 |
| Research credit | `f00dat` |
| Disclosure platform | YesWeHack |
| Fix | Apache Log4net 3.3.0 |
| Public verification | Apache advisory, NVD, GitHub Advisory, fix pull request, and oss-security disclosure |

> The Web2 section currently highlights publicly verifiable work. Additional private, pending, rejected, or embargoed research is intentionally not represented as validated portfolio evidence.

---

# Research Focus

| Area | Focus |
|---|---|
| Smart Contracts and DeFi | Authorization, state transitions, share pricing, dilution, settlement, recapitalization, asset ownership, and economic invariants |
| Cross-Chain Systems | Message validation, replay protection, destination binding, distributed accounting, bridge invariants, and token-wrapper trust boundaries |
| Blockchain Infrastructure | Consensus, block validation, signer identity, node behavior, P2P protocols, mining coordination, and reorg safety |
| Governance Systems | Voting arithmetic, membership integrity, proposal lifecycle, staking transitions, cleanup safety, and emergency liveness |
| Web2 Security | Application security, attacker-controlled input handling, logging and telemetry integrity, parser and serialization behavior, safe failure modes, and coordinated vulnerability disclosure |
| Proof Development | Reproducible end-to-end proofs using real protocol paths whenever possible, with explicit controls, measurable state transitions, and bounded impact claims |

---

# Research Standard

Only findings meeting at least one of these conditions are included:

1. Officially validated by a bug bounty program
2. Accepted in a public audit contest
3. Confirmed as a duplicate of a valid issue
4. Assigned a public CVE
5. Supported by public evidence after disclosure is permitted

Private, pending, rejected, and embargoed reports are excluded.

### Evidence Principles

- Public evidence is preferred whenever disclosure is permitted.
- Final severity totals follow the official contest or program classification.
- Submitted severity is retained when it is relevant to a documented severity disagreement.
- Reward amounts are recorded for transparency, while technical impact remains the primary portfolio signal.
- Reproduction paths and PoCs are presented with explicit controls, measurable state transitions, and bounded impact claims.

---

# Contact

[![GitHub](https://img.shields.io/badge/GitHub-f00dat-181717?style=for-the-badge&logo=github)](https://github.com/f00dat)
[![DEV](https://img.shields.io/badge/DEV-Technical_Writeups-0A0A0A?style=for-the-badge&logo=devdotto)](https://dev.to/f00dat)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Daniel_Alves-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/danielalvesads/)

---

Research handle: `f00dat`  
Web3 and Web2 security research portfolio built around reproducibility, public evidence, measurable impact, and technically bounded claims.
