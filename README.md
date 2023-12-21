
## Audit experience
- Experienced security researcher with a solid two-year background in blockchain security, specializing in Defi, Cross-chain, and various protocols. Started as a white-hat on Immunefi in late 2021, successfully addressing vulnerabilities in prominent protocols like AAVE and RAI (see Bug Bounties section for disclosures/write-ups). Currently, a Smart Contract Auditor at Oak Security/Solidified since January 2023, conducting code reviews publicly accessible through provided links. Also, an EVM & Security Researcher at Turing Consulting since July 2023, responsible for protocol optimization, low-level assembly auditing (Yul, sometimes Huff), and providing security consultancy for the Unlockd Protocol. Secured two AAVE grants for contributions to fortifying AAVE v3-token and AAVE Starknet bridge. Additionally, skilled in zk circom circuits, audited them, and a zkyAcademy block 1 fellow with experience in auditing cryptographic primitives libraries. Formerly a full-stack developer before entering the blockchain environment.

### External audits

| Company |  Certora, AAVE |
|------------|-----------------|
| Protocol name and type | aave-token v3  |
| Link | https://github.com/Elpacos/aave-token-v3/tree/certora-community, https://github.com/Certora/aave-token-v3/blob/main/certora/reports/Formal_Verification_Report_AAVE_Token_V3.pdf |  
| Reflection | Implemented 21 formal rules and unveiled a high severity Issue on the AAVE token under the github nickname "Elpacos", won first place out of 20 participants of the AAVE grant. |     

| Company |  Certora, AAVE |
|------------|-----------------|
| Protocol name and type | aave-starknet: bridge  |
| Link | https://github.com/Elpacos/aave-token-v3/tree/certora-community, https://github.com/aave-starknet-project/aave-starknet-bridge/blob/main/audit/certora_report.pdf |  
| Reflection | Implemented 18 formal rules to verify the codebase, scored sixth place out of +20 participants of the AAVE grant. |   

| Company |  Certora |
|------------|-----------------|
| Protocol name and type | Blockswap Formal Verification, a permissionless 3 pool liquid staking solution for Ethereum.  |
| Link | https://github.com/Certora/2023-01-blockswap-fv/blob/certora/certora/specs/Syndicate.spec |  
| Reflection | Implemented 10 formal rules added to the final spec of the Syndicate codebase. |     

| Company |  Oak Security / Solidified |
|------------|-----------------|
| Protocol name and type | Mauve & Violet: uniswap v3 fork with KYC   |
| Link | https://github.com/solidified-platform/audits/blob/master/Audit%20Report%20-%20Mauve.pdf  |  

| Company |  yAcademy |
|------------|-----------------|
| Protocol name and type | exit10: boostraping   |
| Link | https://reports.yaudit.dev/reports/04-2023-Exit10/  |  

| Company |  yAcademy |
|------------|-----------------|
| Protocol name and type | VMEX: AAVE v2 fork   |
| Link | https://reports.yaudit.dev/reports/06-2023-VMEX/  |  
| Reflection | Found a unique [high severity issue](https://reports.yaudit.dev/reports/06-2023-VMEX/#4-high---incorrect-order-of-arguments-in-calls-to-incentivescontrollerhandleaction) on top of the residents' findings. |   
  
| Company |  Oak Security / Solidified |
|------------|-----------------|
| Protocol name and type |  Xaya Democrit, Gaming rollup L1 contracts |
| Link |  https://github.com/solidified-platform/audits/blob/master/Audit%20Report%20-%20Xaya%20Democrit.pdf  |

| Company |  Turing Consulting |
|------------|-----------------|
| Protocol name and type |  MaxApy (Assembly gas optimisation): DeFI strategies aggregator |
| Link |  Report Not Public, https://goerli.maxapy.io/  |
| Reflection | Implemented a big part of the protocol with inline assembly following the best security and optimisation practices, in order to decrease gas costs up to 67% on main user functions.|

| Company |  Turing Consulting |
|------------|-----------------|
| Protocol name and type |  Unlockd v2 (Gas optimisation): NFT borrowing and lending |
| Link |  Report Not Public, https://twitter.com/Unlockd_Finance, https://github.com/UnlockdFinance/unlockd  |
| Reflection | Optimised the protocol code as much as is possible with solidity, reducing users gas costs up to 36%. |

| Company |  Oak Security / Solidified |
|------------|-----------------|
| Protocol name and type |  HAI: Stablecoin, RAI fork on Optimism |
| Link |  Report Not Public Yet, https://github.com/hai-on-op/core, [Unique critical issue found by me](https://x.com/DeFi_Wonderland/status/1733179127690059909?s=20)  |
| Reflection | Audited in parallel with two other companies, I found two unique high severity issues on top of the other auditors.|


| Company | C4 contest |
|------------|-----------------|
| Protocol name and type |  OpenDollar: Stablecoin |
| Link |  https://code4rena.com/audits/2023-10-open-dollar#top  |
| Reflection | Despite my usual focus on bug bounties and security reviews, I came across a high-severity issue identified only by another warden. This finding earned a spot in the official report and achieved a noteworthy sixth place in the contest rankings. |

| Company |  Turing Consulting |
|------------|-----------------|
| Protocol name and type |  Sablier: v2 changelog audit |
| Link |  https://github.com/sablier-labs/audits/blob/main/v2-core/turing-2023-11-30.pdf, https://github.com/sablier-labs/audits/blob/main/v2-periphery/turing-2023-11-30.pdf |

| Company | Independent audit |
|------------|-----------------|
| Protocol name and type |  Unhosted Wallet: AA wallet with defi integrations |
| Link |  https://github.com/Unhosted-Wallet/unhosted-modules/blob/main/defi-strategies/audits/Unhosted_Wallet_Modules_Security_Review_Report_vnmrtz(final).pdf  |

| Company | Turing Consulting |
|------------|-----------------|
| Protocol name and type |  Unlockd (Continuous security engagement), NFT Lending and borrowing |
| Link | https://twitter.com/Unlockd_Finance  |
| Reflection | Providing in-house security and consultancy services for the Unlockd Protocol. |


## Bug Bounties

| Date       |   July 2022  |  
|------------|-----------------|	
| Protocol name and type | [HIGH] AAVE v3 token, DeFi Lending and Borrowing |
| Link | https://x.com/vn_martinez_/status/1683505277818003458?s=20  |
| Reflection | Found a high severity issue on the AAVE token, which was later fixed by the AAVE team. "Wrong parameter order on delegations". This was the first high severity on a live / ready to deploy protocol I have ever found. Working with the certora team was a great experience.|

| Date       |   October 2023  |  
|------------|-----------------|	
| Protocol name and type | [HIGH] RAI (debt auctions bug), non-pegged stable-coin |
| Link | https://mirror.xyz/vnmrtz.eth/WXm4QJFInoB992czPniFbQyAkGUkdoaSd5zEjK5uRIo  |
| Reflection | Discovered a high severity bug latent in the RAI stablecoin protocol. This flaw led to an unintended overinflation of the protocol token, and notably, it was introduced following a recommendation from OpenZeppelin. |

| Date       |   November 2023  |  
|------------|-----------------|	
| Protocol name and type | [HIGH]  TAI (debt auctions bug), stablecoin |
| Link | Private, https://tai.money/  |
| Reflection | Given that TAI is a fork of RAI, I ensured that the identified bug in the RAI protocol was also addressed in the TAI protocol. |

| Date       |   December 2023  |  
|------------|-----------------|	
| Protocol name and type | [CRITICAL] RAI (liquidations DOS, GEB framework zero day), non-pegged stable-coin  |
| Link | https://x.com/vn_martinez_/status/1733242624117477790?s=20  |
| Reflection | Discovered a critical severity bug latent in the GEB framework of the RAI stablecoin. This flaw led to a SAFE being able to avoid liquidations between a debt threshold. In tandem with the team at defi wonderland, who fowarded the issue to RAI, the RAI team managed to fix the issue on their ungoverned protocol. This has been the most significant bug I have ever found, securing +33M  of TVL at risk. |

## Public Content

### Talks and seminars
I have delivered talks and seminars focusing on EVM and smart contract security. Here are some notable sessions:
- [Calyptus] [Mastering fuzzing](https://github.com/Elpacos/mastering-fuzzing)
- [Opensense] [Low-level vulnerabilities](https://www.youtube.com/watch?v=13YQZ9E05tQ&t=1758s)
- [Secureum: TrustX 2023] [Tips to master fuzzing](https://www.youtube.com/watch?v=gUIZUOBXJvo&t=282s)

### Articles and writeups
My collection of articles on EVM and security, along with detailed write-ups of publicly disclosed bugs available on my [blog](https://mirror.xyz/vnmrtz.eth):
- [Celer cBridge whitehat cheat sheet](https://mirror.xyz/vnmrtz.eth/1oIa86KEaaO-6eonwOqs1lV8SN8cgjKufIAT1b8TtyA)
- [EVM: Degen Bit Masking](https://mirror.xyz/vnmrtz.eth/AoLcp1c_-gxxvGQyIjnvWouXRyIqt8Q9JULv4Mz7Jsk)
- [RAI debt auctions bug writeup](https://mirror.xyz/vnmrtz.eth/WXm4QJFInoB992czPniFbQyAkGUkdoaSd5zEjK5uRIo)
