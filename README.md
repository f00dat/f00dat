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
| Valid and rewarded audit contest findings | 8 |
| Valid and rewarded Web3 bug bounty findings | 1 |
| Published technical writeups | 9 |
| Public CVEs | 1 |
| Documented rewards | $1,045.25 |

> Final severities reflect the official classification assigned by the contest, program, or vendor. Private, pending, rejected, and embargoed reports are not included.

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

### Contest Totals

| Severity | Count |
|---|---:|
| Critical | 2 |
| High | 5 |
| Medium | 1 |
| **Total findings** | **8** |
| **Total rewards** | **$945.25** |

## Web3 Bug Bounty Research

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
| High | 5 |
| Medium | 1 |
| Low | 1 |
| **Total validated findings** | **9** |
| **Total documented rewards** | **$1,045.25** |
| **Published technical writeups** | **9** |

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
