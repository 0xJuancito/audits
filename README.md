# Smart Contract Audits and Findings by 0xJuancito

Reach out on Twitter [@0xJuancito](https://twitter.com/0xJuancito) for security consulting and private audits.

## Audit Competitions

| Project | Severity | Contest | Finding | Notes |
| --- | --- | --- | --- | --- |
| Frankencoin | High | Code4rena | [Fresh positions can be instantly challenged leading to unrestricted minting of ZCHF tokens](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/309) |  |
| Frankencoin | High | Code4rena | [Position owners can perform a sandwich attack against challengers to steal their collateral](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/572) | |
| Frankencoin | High | Code4rena | [Adjusting position prices can lead to unavertable challenges that the protocol will have to pay for](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/566) | Duplicate¹ |
| Frankencoin | High | Code4rena | [Lack of validation in opening positions parameters can lead to critical vulnerabilities at protocol level](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/954) | Duplicate¹ |
| Frankencoin | Medium | Code4rena | [`restructureCapTable()` only wipes out the first address on the list](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/989) | |
| Frankencoin | Medium | Code4rena | [No way to transfer minter role or rennounce to it](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/990) | |
| Frankencoin | QA | Code4rena | [QA Report](https://github.com/code-423n4/2023-04-frankencoin-findings/blob/main/data/juancito-Q.md) | [📝 Selected for Report](https://code4rena.com/reports/2023-04-frankencoin#low-risk-and-non-critical-issues) |
| Footium | Medium | Sherlock | [Some ERC20 tokens can get permanently stuck in the contract due to use of `transfer()`](https://github.com/sherlock-audit/2023-04-footium-judging/issues/252) | |
| Footium | Medium | Sherlock | [Increasing _`maxGenerationId` allows extra minting of academy players on previous seasons](https://github.com/sherlock-audit/2023-04-footium-judging/issues/277) | |
| Footium | Medium | Sherlock | [One extra academy player can be minted per season due to mischeck in `mintPlayers`](https://github.com/sherlock-audit/2023-04-footium-judging/issues/273) | |
| Gravita | Low | Hats | [Out of gas in collectFees](https://github.com/Gravita-Protocol/Gravita-SmartContracts/issues/222) | |
| Teller | High | Sherlock | [Borrowers can steal lenders principal without providing collateral by frontrunning `lenderAcceptBid` and updating the bid](https://github.com/sherlock-audit/2023-03-teller-judging/issues/250) | |
| Teller | High | Sherlock | [Adversary can modify the commited collateral of any bid at any time leading to lost or locked assets and DOS of the protocol](https://github.com/sherlock-audit/2023-03-teller-judging/issues/280) | |
| Teller | Medium | Sherlock | [Marketplaces owners can frontrun `submitBid` to steal collateral by modifying market parameters](https://github.com/sherlock-audit/2023-03-teller-judging/issues/289) | |
| Caviar Private Pools | Medium | Code4rena | [Adversary can prevent the creation of any private pools by frontrunning the deployer](https://github.com/code-423n4/2023-04-caviar-findings/issues/567) | |
| Canto Identity Subprotocols | Medium | Code4rena | [Users can end up buying and paying for a different Tray than the one they were trying to acquire](https://github.com/code-423n4/2023-03-canto-identity-findings/issues/130) | [📝 Selected for report](https://code4rena.com/reports/2023-03-canto-identity#m-07-users-can-end-up-buying-and-paying-for-a-different-tray-than-the-one-they-were-trying-to-acquire) |
| Neo Tokyo | High | Code4rena | [A malicious user can mint a huge amount of BYTES 2.0 tokens for himself](https://github.com/code-423n4/2023-03-neotokyo-findings/issues/366) | |
| Neo Tokyo | High | Code4rena | [Malicious users can claim BYTES rewards after withdrawing all of their LP stake](https://github.com/code-423n4/2023-03-neotokyo-findings/issues/374) | Duplicate¹ |
| Wenwin | QA | Code4rena | [QA Report](https://github.com/code-423n4/2023-03-wenwin-findings/blob/main/data/juancito-Q.md) | |
| Hats | Medium | Sherlock | [Transactions will be frozen if incorrect settings are used during a deployment on HatsSignerGateFactory](https://github.com/sherlock-audit/2023-02-hats-judging/issues/78) | |
| Biconomy | QA | Code4rena | [QA Report](https://github.com/code-423n4/2023-01-biconomy-findings/blob/main/data/juancito-Q.md) | |
| Stader Labs | | Code4rena | [Judging TBA](https://code4rena.com/contests/2023-06-stader-labs#top) | |
| USSD | | Sherlock | [Judging TBA](https://app.sherlock.xyz/audits/contests/82) | |
| EigenLayer | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-04-eigenlayer-contest#top) | |
| EigenLayer | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-04-eigenlayer-contest#top) | |
| EigenLayer | QA | Code4rena | [Report TBA](https://code4rena.com/contests/2023-04-eigenlayer-contest#top) | |
| Rubicon v2 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-04-rubicon-v2#top) | |
| Rubicon v2 | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-04-rubicon-v2#top) | |
| Rubicon v2 | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-04-rubicon-v2#top) | |
| Ajna | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-05-ajna-protocol#top) | |
| Ajna | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-05-ajna-protocol#top) | |
| Contest 225 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | QA | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Polynomial | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-polynomial-protocol-contest#top) | |
| Polynomial | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-polynomial-protocol-contest#top) | |
| Polynomial | QA | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-polynomial-protocol-contest#top) | |
| Asymmetry | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-asymmetry-contest) | |
| Asymmetry | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-asymmetry-contest) | |
| Asymmetry | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-asymmetry-contest) | |
| Asymmetry | QA | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-asymmetry-contest) | |

¹ Issues marked as `Duplicate` are valid issues that have been grouped by contest judges, but carry no extra prize.
