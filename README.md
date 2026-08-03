# Daniel Alves | Security Researcher

![Web3 Security](https://img.shields.io/badge/Web3-Security-6f42c1?style=for-the-badge)
![Blockchain Security](https://img.shields.io/badge/Blockchain-Security-7c3aed?style=for-the-badge)
![DeFi Security](https://img.shields.io/badge/DeFi-Security-f59e0b?style=for-the-badge)
![Smart Contract Auditing](https://img.shields.io/badge/Smart_Contract-Auditing-2ea44f?style=for-the-badge)
![Web2 Research](https://img.shields.io/badge/Web2-Vulnerability_Research-2563eb?style=for-the-badge)
![Public CVE](https://img.shields.io/badge/Public_CVE-1-b91c1c?style=for-the-badge)

Independent security researcher focused on smart contract vulnerabilities, DeFi accounting, blockchain infrastructure, asynchronous protocol integrations, and reproducible proof of concept development.

This portfolio contains only publicly verifiable results.

[Verified Portfolio](#verified-portfolio) · [Audit Contest Research](#audit-contest-research) · [Public CVE](#public-cve) · [Research Focus](#research-focus) · [Contact](#contact)

## Verified Portfolio

| Result | Count |
|---|---:|
| Valid and rewarded audit contest findings | 3 |
| Published technical writeups | 3 |
| Public CVEs | 1 |
| Documented contest rewards | $432.16 |

> Final severities reflect the official classification assigned by the contest or vendor. Private, pending, rejected, and embargoed reports are not included.

## Audit Contest Research

### HackenProof | 0xMarkets

Three High severity findings from the 0xMarkets audit contest have been validated, rewarded, and documented publicly.

| Finding | Final Severity | Reward | Technical Writeup |
|---|---:|---:|---|
| Stale GLV share pricing captured pending insurance recapitalization | High | $343.64 | [Read](https://dev.to/f00dat/how-stale-glv-share-pricing-allowed-new-depositors-to-capture-pending-insurance-recapitalization-5fn6) |
| WNT collateral orders reimbursed an execution fee already funded by the main account | High | $60.87 | [Read](https://dev.to/f00dat/how-wnt-collateral-orders-let-subaccounts-claim-execution-fees-they-never-paid-5241) |
| Pending 0xMarkets request value enabled CarthaVault share inflation | High | $27.65 | [Read](https://dev.to/f00dat/how-pending-0xmarkets-requests-enabled-share-inflation-in-carthavault-5352) |
| **Total** | **3 High** | **$432.16** | **3 articles** |

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
| Cross chain systems | Message validation, replay protection, accounting, and destination binding |
| Web2 security | Application security, logging integrity, and coordinated disclosure |
| Proof development | Reproducible end to end proofs using real protocol paths whenever possible |

## Disclosure Standard

Only findings that are officially validated, accepted in a contest, confirmed as duplicates, assigned a public CVE, or supported by public evidence are added to this portfolio.

Public writeups are released only after disclosure is permitted.

## Contact

[GitHub](https://github.com/f00dat) · [DEV Community](https://dev.to/f00dat) · [LinkedIn](https://www.linkedin.com/in/danielalvesads/)
