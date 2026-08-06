# Daniel Alves | Security Researcher

![Web3 Security](https://img.shields.io/badge/Web3-Security-6f42c1?style=for-the-badge)
![Blockchain Security](https://img.shields.io/badge/Blockchain-Security-7c3aed?style=for-the-badge)
![DeFi Security](https://img.shields.io/badge/DeFi-Security-f59e0b?style=for-the-badge)
![Smart Contract Auditing](https://img.shields.io/badge/Smart_Contract-Auditing-2ea44f?style=for-the-badge)
![Web2 Research](https://img.shields.io/badge/Web2-Vulnerability_Research-2563eb?style=for-the-badge)
![Public CVE](https://img.shields.io/badge/Public_CVE-1-b91c1c?style=for-the-badge)

Independent security researcher focused on smart contract vulnerabilities, DeFi accounting, blockchain infrastructure, asynchronous protocol integrations, cross-chain systems, and reproducible proof of concept development.

This portfolio contains only publicly verifiable results.

[Verified Portfolio](#verified-portfolio) · [Audit Contest Research](#audit-contest-research) · [Web3 Bug Bounty Research](#web3-bug-bounty-research) · [Public CVE](#public-cve) · [Research Focus](#research-focus) · [Contact](#contact)

## Verified Portfolio

| Result | Count |
|---|---:|
| Valid audit contest findings | 15 |
| Rewarded audit contest findings | 14 |
| Valid and rewarded Web3 bug bounty findings | 2 |
| Published technical writeups | 17 |
| Public CVEs | 1 |
| Documented rewards | $1,797.64 |

> Final severities reflect the official classification assigned by the contest, program, or vendor. Private, pending, rejected, and embargoed reports are not included. Valid findings without a payout are tracked separately and do not increase documented rewards.

## Audit Contest Research

### HackenProof | 0xMarkets

Six findings from the 0xMarkets Audit Contest have been validated, rewarded, and documented publicly.

| Finding | Final Severity | Reward | Technical Writeup |
|---|---:|---:|---|
| Stale GLV share pricing captured pending insurance recapitalization | High | $343.64 | [Read](https://dev.to/f00dat/how-stale-glv-share-pricing-allowed-new-depositors-to-capture-pending-insurance-recapitalization-5fn6) |
| WNT collateral orders reimbursed an execution fee already funded by the main account | High | $60.87 | [Read](https://dev.to/f00dat/how-wnt-collateral-orders-let-subaccounts-claim-execution-fees-they-never-paid-5241) |
| Pending 0xMarkets request value enabled CarthaVault share inflation | High | $27.65 | [Read](https://dev.to/f00dat/how-pending-0xmarkets-requests-enabled-share-inflation-in-carthavault-5352) |
| WNT execution fees were sent to CarthaVault instead of the request vaults | Medium | $0.92 | [Read](https://dev.to/f00dat/how-a-wrong-wnt-receiver-broke-carthavaults-nonzero-execution-fee-paths-4156) |
| Transferred CarthaVault shares became permanently unredeemable after the original Position was deleted | High | $0.19 | [Read](https://dev.to/f00dat/how-transferred-carthavault-shares-became-permanently-unredeemable-133n) |
| A 1e12 GM decimal mismatch let existing LPs capture later deposits | High | $0.01 | [Read](https://dev.to/f00dat/how-a-1e12-decimal-mismatch-let-existing-lps-capture-later-deposits-57fm) |
| **0xMarkets total** | **5 High · 1 Medium** | **$433.28** | **6 articles** |

### HackenProof | Overlayer DualDefense

| Finding | Final Severity | Reward | Public Evidence |
|---|---:|---:|---|
| Destination-local `totalBridgedOut` underflow permanently stranded first inbound transfers | Critical | $68.97 | [Article](https://dev.to/f00dat/how-overlayers-destination-local-counter-permanently-stranded-first-inbound-transfers-7i7) · [Report](https://hackenproof.com/reports/OVLRSCDD-30) |
| **Overlayer total** | **1 Critical** | **$68.97** | **1 article** |

### HackenProof | ZIGChain Code DualDefense

| Finding | Final Severity | Reward | Public Evidence |
|---|---:|---:|---|
| Base-denom-only validation let untrusted IBC vouchers drain native tokenwrapper reserves | Critical | $443.00 | [Article](https://dev.to/f00dat/how-a-base-denom-collision-let-untrusted-ibc-vouchers-drain-zigchains-native-reserves-3o5j) · [Report](https://hackenproof.com/reports/ZIGCHDD-74) |
| **ZIGChain total** | **1 Critical** | **$443.00** | **1 article** |

### Code4rena | Panoptic: Next Core

| Finding | Final Severity | Reward | Public Evidence |
|---|---:|---:|---|
| Reinitializable `BuilderWallet` let anyone replace the admin and steal builder fee balances | High | No payout | [Article](https://dev.to/f00dat/how-a-reinitializable-builderwallet-let-anyone-steal-builder-fees-586d) · [Final Report](https://code4rena.com/reports/2025-12-panoptic-next-core#h-01-builderwallet-init-is-unprotectedre-initializable-enabling-takeover-and-theft-of-builder-fees) |
| **Panoptic total** | **1 High** | **No payout** | **1 article** |

> Code4rena included the issue as `H-01` in the final report and credited `I1iveF0rTh1Sh1t` among the researchers who identified it. The finding remained High, while the contest dashboard showed no earnings for this submission.

### Code4rena | Rujira

Code4rena credited `I1iveF0rTh1Sh1t` with three High and three Medium findings in the Rujira audit, finishing in 25th place with $252.39 in total contest earnings.

| Finding | Final Severity | Reward | Public Evidence |
|---|---:|---:|---|
| Borrow limit can be bypassed via share rounding and floored ownership accounting | Medium | Included in contest total | [Article](https://dev.to/f00dat/how-share-rounding-let-a-rujira-borrower-take-2-tokens-with-a-limit-of-1-22h9) · [Contest Results](https://code4rena.com/audits/2025-12-rujira) |
| `adjusted_ltv()` can divide by zero and panic, DoSing queries and safety-check/liquidation flows | Medium | Included in contest total | [Article](https://dev.to/f00dat/how-zero-adjusted-collateral-could-dos-rujira-credit-queries-and-liquidations-1ipa) · [Contest Results](https://code4rena.com/audits/2025-12-rujira) |
| Repayment can be permanently blocked by rounding and repay clamping (`permanent dust debt` DoS) | Medium | Included in contest total | [Article](https://dev.to/f00dat/how-repay-clamping-created-permanent-dust-debt-in-rujira-ghost-vault-53fh) · [Contest Results](https://code4rena.com/audits/2025-12-rujira) |
| Borrower can brick liquidation by storing an invalid preference `LiquidateMsg::Repay` | High | Included in contest total | [Article](https://dev.to/f00dat/how-a-borrower-controlled-repay-preference-could-brick-rujira-liquidations-552j) · [Contest Results](https://code4rena.com/audits/2025-12-rujira) |
| Liquidator can extract a hidden bonus up to `liquidation_max_slip` by draining collateral while repaying debt with external funds | High | Included in contest total | [Article](https://dev.to/f00dat/how-rujiras-slippage-guard-could-become-a-hidden-liquidation-bonus-58j4) · [Contest Results](https://code4rena.com/audits/2025-12-rujira) |
| Borrower-controlled unbounded `preference_msgs` can make liquidations economically unexecutable because preferences execute before solver steps | High | Included in contest total | [Article](https://dev.to/f00dat/how-unbounded-borrower-preferences-could-make-rujira-liquidations-economically-impossible-4cf5) · [Contest Results](https://code4rena.com/audits/2025-12-rujira) |
| **Rujira total** | **3 High · 3 Medium** | **$252.39** | **6 findings · 6 articles** |

> The published contest results verify the complete Rujira result. All six findings are now documented in public technical writeups: three High findings covering the invalid-repay liquidation blocker, the hidden liquidation bonus, and the unbounded-preference liquidation DoS, plus three Medium findings covering the borrow-limit rounding bypass, the zero-adjusted-collateral panic, and the permanent dust-debt repayment DoS.

### Contest Totals

| Severity | Count |
|---|---:|
| Critical | 2 |
| High | 9 |
| Medium | 5 |
| **Total valid findings** | **15** |
| **Rewarded findings** | **14** |
| **Total rewards** | **$1,197.64** |

## Web3 Bug Bounty Research

### CertiK Skynet | WEMIX

| Finding | Submitted Severity | Final Severity | Reward | Public Evidence |
|---|---:|---:|---:|---|
| Removed validator remained accepted as an active signer and reward recipient after `GovImp` self-change corrupted validator index alignment | Critical | Medium | $500.00 | [Article](https://dev.to/f00dat/how-wemix-kept-accepting-a-removed-validator-as-an-active-signer-1135) · [Public Report](https://gist.github.com/f00dat/96219a676da64aeef5eadf174cb0b442) |
| **WEMIX total** |  | **1 Medium** | **$500.00** | **1 article** |

> The report was submitted as Critical because a legitimate governance removal did not revoke the validator from the real client-side active-enode path. The proof demonstrated that `enodeExists` continued accepting the removed enode and that the reward path attributed a positive reward to the removed validator’s chosen address using another active validator’s stake. WEMIX assigned the final severity as Medium and paid a $500 bounty. The published writeup documents the technical basis for the Critical classification and the repeated severity-downgrade pattern observed across my WEMIX submissions.

### HackenProof | Momentum

| Finding | Submitted Severity | Final Severity | Reward | Technical Writeup |
|---|---:|---:|---:|---|
| Zero-liquidity `flash_swap` crossed initialized ticks for free, mutated oracle state, and could stall reward claimability | High | Low | $100.00 | [Read](https://dev.to/f00dat/how-a-zero-liquidity-flash-swap-crossed-momentum-ticks-for-free-and-stalled-rewards-4369) |
| **Momentum total** |  | **1 Low** | **$100.00** | **1 article** |

> The report was submitted as High with a CVSS v3.1 score of 7.5. HackenProof kept the official severity at Low, citing the requirement for zero active liquidity and the absence of demonstrated direct theft. The published article documents the free tick crossing, oracle mutation, zero-debt receipt, and the later proof showing rewards becoming unclaimable until administrator intervention.

## Portfolio Totals

| Severity | Count |
|---|---:|
| Critical | 2 |
| High | 9 |
| Medium | 4 |
| Low | 1 |
| **Total validated findings** | **17** |
| **Rewarded findings** | **16** |
| **Total documented rewards** | **$1,797.64** |
| **Published technical writeups** | **17** |

## Public CVE

### CVE 2026 40021 | Apache Log4net

**Silent loss of log events in `XmlLayout` and `XmlLayoutSchemaLog4J` caused by unescaped XML 1.0 forbidden characters**

| Field | Details |
|---|---|
| Product | Apache Log4net |
| Vendor severity | Medium |
| CVSS 4.0 | 6.3 |
| Affected versions | Versions before 3.3.0 |
| Fixed version | 3.3.0 |
| Research credit | f00dat |
| Disclosure platform | YesWeHack |

Attacker influenced MDC property keys, MDC values, and identity data could introduce XML 1.0 forbidden characters. The resulting serialization exception could silently suppress individual log records, weakening audit trails and malicious activity detection.

**References:** [Apache Advisory](https://logging.apache.org/security.html#CVE-2026-40021) · [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-40021) · [GitHub Advisory](https://github.com/advisories/GHSA-4f7c-pmjv-c25w) · [Fix Pull Request](https://github.com/apache/logging-log4net/pull/280) · [oss security](https://www.openwall.com/lists/oss-security/2026/04/10/11)

## Research Focus

| Area | Focus |
|---|---|
| Smart contracts | Authorization, state transitions, accounting, and economic invariants |
| DeFi and vaults | Share pricing, dilution, settlement, recapitalization, and asset ownership |
| Asynchronous integrations | Pending requests, keeper workflows, and ordering windows |
| Blockchain infrastructure | Consensus, node behavior, protocol validation, and edge cases |
| Cross-chain systems | Message validation, distributed state, replay protection, accounting, and destination binding |
| Web2 security | Application security, logging integrity, and coordinated disclosure |
| Proof development | Reproducible end-to-end proofs using real protocol paths whenever possible |

## Disclosure Standard

Only findings that are officially validated, accepted in a contest, confirmed as duplicates, assigned a public CVE, or supported by public evidence are added to this portfolio.

Public writeups are released only after disclosure is permitted.

## Contact

[GitHub](https://github.com/f00dat) · [DEV Community](https://dev.to/f00dat) · [LinkedIn](https://www.linkedin.com/in/danielalvesads/)
