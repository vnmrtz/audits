# Audit Experience

## Overview
Experienced security researcher & solidity white-hat with a robust two-year background in blockchain security. Started as a white-hat on Immunefi in late 2021, successfully addressing vulnerabilities in prominent protocols like AAVE and RAI (see [Bug Bounties section](#bounties)), securing +33M USD live at risk. Current roles include Smart Contract Auditor at Oak Security/Solidified and EVM & Security Researcher at Turing Consulting. 

## External Audits

### Aave-token v3
- **Company:** Certora, AAVE
- **Link:** [GitHub](https://github.com/Elpacos/aave-token-v3/tree/certora-community), [Report](https://github.com/Certora/aave-token-v3/blob/main/certora/reports/Formal_Verification_Report_AAVE_Token_V3.pdf)
- **Reflection:** Identified a high-severity issue, won first place in AAVE grant.

### Aave-starknet: bridge
- **Company:** Certora, AAVE
- **Link:** [GitHub](https://github.com/Elpacos/aave-token-v3/tree/certora-community), [Report](https://github.com/aave-starknet-project/aave-starknet-bridge/blob/main/audit/certora_report.pdf)
- **Reflection:** Implemented 18 formal rules, achieved sixth place in AAVE grant.

### Blockswap Formal Verification
- **Company:** Certora
- **Link:** [GitHub](https://github.com/Certora/2023-01-blockswap-fv/blob/certora/certora/specs/Syndicate.spec)
- **Reflection:** Implemented 10 formal rules for Syndicate codebase.

### Mauve & Violet: uniswap v3 fork with KYC
- **Company:** Oak Security/Solidified
- **Link:** [Report](https://github.com/solidified-platform/audits/blob/master/Audit%20Report%20-%20Mauve.pdf)

### exit10: boostraping
- **Company:** yAcademy
- **Link:** [Report](https://reports.yaudit.dev/reports/04-2023-Exit10/)

### VMEX: AAVE v2 fork
- **Company:** yAcademy
- **Link:** [Report](https://reports.yaudit.dev/reports/06-2023-VMEX/)
- **Reflection:** Found a unique high-severity issue.

### Xaya Democrit, Gaming rollup L1 contracts
- **Company:** Oak Security/Solidified
- **Link:** [Report](https://github.com/solidified-platform/audits/blob/master/Audit%20Report%20-%20Xaya%20Democrit.pdf)

### MaxApy (Assembly gas optimisation): DeFI strategies aggregator
- **Company:** Turing Consulting
- **Link:** Report Not Public, [Website](https://goerli.maxapy.io/)
- **Reflection:** Decreased gas costs up to 67% on main user functions.

### Unlockd v2 (Gas optimisation): NFT borrowing and lending
- **Company:** Turing Consulting
- **Link:** Report Not Public, [Twitter](https://twitter.com/Unlockd_Finance), [GitHub](https://github.com/UnlockdFinance/unlockd)
- **Reflection:** Reduced users' gas costs up to 36%.

### HAI: Stablecoin, RAI fork on Optimism
- **Company:** Oak Security/Solidified
- **Link:** Report Not Public Yet, [GitHub](https://github.com/hai-on-op/core), [Issue](https://x.com/DeFi_Wonderland/status/1733179127690059909?s=20)
- **Reflection:** Found two unique high-severity issues.

### OpenDollar: Stablecoin
- **Company:** C4 contest
- **Link:** [Contest Page](https://code4rena.com/audits/2023-10-open-dollar#top)
- **Reflection:** Despite my usual focus on bug bounties and security reviews, I came across a high-severity issue identified only by another warden. This finding earned a spot in the official report and achieved a noteworthy sixth place in the contest rankings.

### Sablier: v2-core & v2-periphery changelog audit
- **Company:** Turing Consulting
- **Link:** [GitHub](https://github.com/sablier-labs/audits/blob/main/v2-core/turing-2023-11-30.pdf), [GitHub](https://github.com/sablier-labs/audits/blob/main/v2-periphery/turing-2023-11-30.pdf)

### Unhosted Wallet: AA wallet with defi integrations
- **Company:** Independent Audit
- **Link:** [GitHub](https://github.com/Unhosted-Wallet/unhosted-modules/blob/main/defi-strategies/audits/Unhosted_Wallet_Modules_Security_Review_Report_vnmrtz(final).pdf)

### Unlockd (Continuous security engagement), NFT Lending and borrowing
- **Company:** Turing Consulting
- **Link:** [Twitter](https://twitter.com/Unlockd_Finance)
- **Reflection:** Providing in-house security and consultancy services for the Unlockd Company.

## <a name="bounties">Bug Bounties</a>

### July 2022
- **Protocol:** [HIGH] AAVE v3 token, DeFi Lending and Borrowing
- **Link:** [Disclosure](https://x.com/vn_martinez_/status/1683505277818003458?s=20)
- **Reflection:** Found a high-severity issue on the AAVE token, fixed by the AAVE team.

### October 2023
- **Protocol:** [HIGH] RAI (debt auctions bug), non-pegged stable-coin
- **Link:** [Write-up](https://mirror.xyz/vnmrtz.eth/WXm4QJFInoB992czPniFbQyAkGUkdoaSd5zEjK5uRIo)
- **Reflection:** Discovered a high-severity bug in RAI, leading to unintended overinflation.

### November 2023
- **Protocol:** [HIGH] TAI (debt auctions bug), stablecoin
- **Link:** Private, [Website](https://tai.money)
- **Reflection:** Addressed the identified bug in the TAI Company.

### December 2023
- **Protocol:** [CRITICAL] RAI (liquidations DOS, GEB framework zero day), non-pegged stable-coin
- **Link:** [Disclosure](https://x.com/vn_martinez_/status/1733242624117477790?s=20)
- **Reflection:** Discovered a critical bug in the GEB framework of the RAI stablecoin, securing +33M of TVL at risk.

## Public Content

### Talks and Seminars
Delivered talks and seminars on EVM and smart contract security:
- [Calyptus] [Mastering Fuzzing](https://github.com/Elpacos/mastering-fuzzing)
- [Opensense] [Low-level Vulnerabilities](https://www.youtube.com/watch?v=13YQZ9E05tQ&t=1758s)
- [Secureum: TrustX 2023] [Tips to Master Fuzzing](https://www.youtube.com/watch?v=gUIZUOBXJvo&t=282s)

### Articles and Write-ups
Collection of articles on EVM and security, along with detailed write-ups of publicly disclosed bugs on [blog](https://mirror.xyz/vnmrtz.eth):
- [Celer cBridge Whitehat Cheat Sheet](https://mirror.xyz/vnmrtz.eth/1oIa86KEaaO-6eonwOqs1lV8SN8cgjKufIAT1b8TtyA)
- [EVM: Degen Bit Masking](https://mirror.xyz/vnmrtz.eth/AoLcp1c_-gxxvGQyIjnvWouXRyIqt8Q9JULv4Mz7Jsk)
- [RAI Debt Auctions Bug Write-up](https://mirror.xyz/vnmrtz.eth/WXm4QJFInoB992czPniFbQyAkGUkdoaSd5zEjK5uRIo)
