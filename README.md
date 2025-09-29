# DumpFun Security Reports

Welcome to the **DumpFun Security Reports** repository.  
This repo exists to coordinate **responsible disclosure** of vulnerabilities and track our bug bounty program.

## 🔒 Responsible Disclosure Policy
- **DO report** any security issues you discover in DumpFun’s on-chain programs, APIs, or frontend.
- **DO NOT exploit** vulnerabilities beyond what is necessary to demonstrate proof of concept.
- **DO NOT disclose publicly** until we have acknowledged, triaged, and fixed the issue (or provided written approval).
- **DO include** clear reproduction steps, transaction IDs, and minimal proof-of-concept code when possible.

## 🏆 Bug Bounty Scope
In scope:
- Solana smart contracts (DumpFun core, buy/sell, lock timers, ramp limits, liquidity pools, fee routing).
- Off-chain infrastructure (APIs, event listeners, indexers).
- App/frontend logic that could lead to **on-chain loss of funds**.

Out of scope:
- Social engineering.
- Denial-of-service against off-chain infrastructure.
- Third-party services not operated by DumpFun.

## 📩 How to Report
- Email us directly: **security@dumpfun.io**
- Or use [GitHub Security Advisories](https://docs.github.com/en/code-security/security-advisories) for confidential reporting.
- Please do not open public GitHub issues for vulnerabilities.

## 🎁 Rewards
Reports are rewarded based on **severity and impact**:
- **Critical:** potential loss of funds, bypass of core mechanics.
- **High:** disruption of program flow, unintended mint/transfer.
- **Medium:** state inconsistencies, manipulation of non-critical data.
- **Low:** informational leaks, non-exploitable bugs.

## 🤝 Acknowledgements
Researchers who responsibly disclose vulnerabilities may be added to our **Hall of Fame** unless they wish to remain anonymous.

## 🔗 Project Links
- [DumpFun App](https://dumpfun.io)
- [Whitepaper / Docs](https://docs.dumpfun.io)
- [Bug Bounty Reports](https://github.com/dumpfun/security-reports)
- [Contact Security](mailto:security@dumpfun.io)
---

**Note:** DumpFun does not take legal action against good-faith security research that follows this policy.
